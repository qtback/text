---
layout: home
title: "상태확인"
keyword: "상태 확인"
---

# 파일의 상태 확인
---
상태 개념은 깃의 분리된 저장 영역인 워킹 디렉터리와 스테이지, 추적 여부를 의미합니다. 깃이 이렇게 다양한 저장 영역을 구분해서 가지고 있는 것은 파일들의 상태를 효율적으로 모니터링하기 위해서입니다. 이번에는 파일들의 상태를 모니터링할 수 있는 status 명령어를 알아봅니다.  

<br>
<a name="1"></a>

## tatus 명령어로 깃 상태 확인
---
파일을 생성하고 수정한다는 것은 변화를 의미합니다. 또 이러한 변화들은 순서가 있습니다. 깃은 각 저장 영역에서 일어나는 다양한 변화를 감시합니다. 그리고 이러한 변화를 감지하고 상태 메시지를 출력합니다.  

status 명령어를 사용하면 깃의 상태 메시지를 확인할 수 있습니다. 특히 status 명령어는 많이 사용하는 깃 명령어 중 하나입니다.  

터미널(깃 배시)에서 status 명령어를 입력합니다.  

```
$ git status ☜ 상태를 확인하는 명령.
On branch master
No commits yet ☜커밋이 없다는 메시지
nothing to commit (create/copy files and use "git add" to track) ☜변경된 내용이 없다는 메시지
```

우리는 처음 깃 저장소를 생성하고, 실습 이후에 아무 작업도 하지 않았습니다. status 명령어를 실행하면 이처럼 변경된 내용과 커밋이 없다고 메시지를 출력할 것입니다. 나중에 커밋 명령을 수행하면 status 명령어로 파일들의 변경된 상태를 확인할 수 있습니다.  

<br>
<a name="2"></a>

## 소스트리에서 깃 상태 확인
---
소스트리를 이용하면 콘솔에서 status 명령어를 입력하지 않고도 바로 깃 상태를 확인할 수 있습니다. 소스트리를 실행한 후 왼쪽의 파일 상태 탭을 선택합니다.  

그림 3-19] 깃 상태 확인  
![깃_상태_확인](./img/sourcetree_status.jpg) 

소스트리는 깃의 파일 상태를 두 영역으로 표시합니다. 스테이지의 tracked와 unmodified 상태는 스테이지에 올라간 파일에 표시합니다. untracked와 modified 상태는 스테이지에 올라가지 않은 파일에 표시합니다.  

새 파일을 추가하면 untracked 상태입니다. 따라서 스테이지에 올라가지 않은 파일 목록에 출력합니다. 스테이지에 올라가지 않은 파일이란 워킹 디렉터리 안에 있는 파일을 의미합니다.  

이처럼 소스트리는 직관적으로 깃에 추가된 파일을 확인할 수 있습니다. status 명령어와 관련된 구체적인 사용법은 실습을 진행해 나가면서 하나씩 설명하겠습니다.  

<br><br>