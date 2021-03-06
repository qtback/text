---
layout: home
title: "Clean"
keyword: "Clean"
---

# 워킹 디렉터리 청소
---
개발하는 과정에서는 컴파일 등 임시로 생성되는 파일들이 생깁니다. 이 파일들은 .gitignore 목록에 넣어 관리할 수도 있지만, 반복해서 불필요하게 생성되는 파일들은 귀찮을 뿐입니다. 이때 clean 명령어를 사용하면 워킹 디렉터리에 있는 추적되지 않는 파일들을 찾아 삭제합니다. clean 명령어를 사용할 때는 주의할 점이 있는데, clean 명령어를 실행하는 순간 워킹 디렉터리의 추적되지 않는 모든 파일을 삭제한다는 것입니다.  

clean 명령어는 단독으로 실행하거나 몇 가지 추가 옵션을 같이 사용할 수 있습니다.  

```
$ git clean
```

실습을 위해 feature 브랜치에 새 파일을 하나 생성합니다.  

```
infoh@DESKTOP MINGW64 /e/gitstudy07 (feature)
$ echo “this is temp” > temp.htm ☜새로운 파일

infoh@DESKTOP MINGW64 /e/gitstudy07 (feature)
$ git status ☜상태확인
On branch feature
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)
        modified:   stash.htm
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        temp.htm ☜ 추적하지 않는 파일
no changes added to commit (use "git add" and/or "git commit -a")

```

새로운 파일을 하나 생성하여 추적되지 않는 새 파일을 만들었습니다. 새로 만든 파일이 불필요해졌습니다. clean 명령어를 사용하여 생성된 untracked 상태의 파일들을 삭제합니다.  

```
infoh@DESKTOP MINGW64 /e/gitstudy07 (feature)
$ git clean
fatal: clean.requireForce defaults to true and neither -i, -n, nor -f given; refusing to clean

```

앗, 삭제 명령이 거부되었습니다. 삭제 명령은 민감해서 몇 가지 옵션을 같이 사용해야 합니다. 어떤 옵션이 있는지 -help 옵션으로 살펴봅시다.

```
$ git clean -help
usage: git clean [-d] [-f] [-i] [-n] [-q] [-e <pattern>] [-x | -X] [--] <paths>...

    -q, --quiet           do not print names of files removed
    -n, --dry-run         dry run
    -f, --force           force
    -i, --interactive     interactive cleaning
    -d                    remove whole directories
    -e, --exclude <pattern>
                          add <pattern> to ignore rules
    -x                    remove ignored files, too
    -X                    remove only ignored files

```

그럼 -f 옵션을 사용하여 강제로 삭제해 보겠습니다.

```
infoh@DESKTOP MINGW64 /e/gitstudy07 (feature)
$ git clean -f
Removing temp.htm
```

추적하지 않는 파일들을 강제로 삭제했습니다. -f 옵션 외에도 다음 옵션을 많이 사용합니다.

* -n 옵션: clean 명령어를 사용하여 잘못 삭제하는 것을 미연에 방지하고자 파일을 가상으로 미리 처리해 보고 사용자에게 확인을 요청합니다.

* -d 옵션: 워킹 디렉터리를 삭제하는 과정에서 새롭게 생성된 파일, 즉 추적되지 않는 파일만 별도로 삭제할 수 있습니다. -d 옵션은 untracked 상태의 파일만 삭제합니다. 이 옵션으로 잘 삭제되지 않는다면 강제 수행 옵션인 -f를 같이 사용할 수도 있습니다.

* -x 옵션: .gitignore 파일은 깃에서 관리하지 않는 파일들의 목록을 정의해 놓은 것입니다. clean 명령어를 수행할 때 .gitignore에 등록한 파일은 삭제하지 않습니다. 이 파일까지 같이 삭제하고 싶다면 -x 옵션을 사용합니다.

>Note: 깃에 저장된 것을 완벽히 삭제하기는 쉽지 않습니다. 깃은 실수로 변경하거나 삭제되는 것을 방지하는 도구입니다. 따라서 좀 더 완벽하게 깃 저장소를 청소하려면 깃의 원리를 이해해야 합니다. 커밋 기록을 완벽하게 제거하고 싶다면 reflog 기록도 같이 삭제해야 합니다. 추가 내용은 이 책의 학습 사이트(https://git.jiny.dev)를 이용합니다.  

<br><br>