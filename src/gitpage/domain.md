---
layout: home
title: "Git 교과서"

keyword: "git, 깃사용법, 깃허브, 소스트리, 깃교과서"
---
## 사이트 접속

### 사이트 URL
깃은 즉각적인 웹사이트 배포를 지원합니다. 깃페이지의 소스를 선택과 저장만으로 사이트의 운영을 바로 시작할 수 있습니다.

깃허브는 웹사이트 접속을 위한 새로운 url을 제공합니다.

https://계정아이디.github.io/저장소명

깃허브의 설정 패이지를 갱신하시면, 깃허브 설정 부분에 다음과 같이 생성된 사이트 접속 url을 확인할 수 있습니다.

 

클릭하여 사이트에 접속을 해봅니다.

 

### 공용도메인
깃허브는 생성되는 모든 저장소에 대해서 자신들만의 고유 주소 도메인을 할당합니다.

https://계정아이디.github.io/저장소명

이때 사용되는 공용도메인은 .io를 가지는 github.io 입니다. 깃허브의 메인사이트 주소인 github.com과 다릅니다.

깃허브에서 제공하는 무료 도메인은 별도의 비용이 들지 않습니다. 

### 도메인 연결
공용 도메인은 별도의 비용을 들이지 않고 웹페이지를 운영할 수 있는 장점입니다. 하지만, 전문적으로 자신의 웹사이트의 정체성을 유지하기 위해서는 독립된 도메인을 사용하고 싶을 것입니다.

깃허브는 자신이 보유하고 있는 도메인을 깃 페이지에 연결을 할 수 있도록 추가 기능을 제공합니다. 저장소 설정에서 깃페이지의 3번째 항목을 살펴 봅니다.

커스텀 도메인 설정부분이 별도 있습니다. 자신이 보유하고 있는 도메인을 입력하시면 됩니다.

 

도메인은 별도의 전문 기관을 통하여 구매를 하셔야 합니다.

### DNS 설정
커스텀 도메인을 깃페이지와 연결을 하기 위해서는 추가로 DNS 설정을 해주어야만 합니다.

DNS는 해당 도메인이 실제 서버를 가지는 깃허브와 연결을 할 수도록 도메인 이름을 해석해 주는 역할을 수행합니다.

만일 자신의 도메인과 연결된 웹서버가 도메인에서 제공해 주는 서버가 아닌 외부의 서버로 연결을 할때는 네임서버 정보를 직접 변경을 해주어야 합니다.

여기서 깃페이지는 도메인 회사의 웹서버가 아니기 때문에 깃허브 네임서버 정보로 네임서버를 변경해야 합니다. 

깃허브의 네임서버 정보를 알기 위해서는 깃허브 도메인 설정 부분에 보면 “learn more” 링크가 있습니다. 이를 클릭하여 깃허브의 네임서버 정보를 확인 하시면 됩니다.

깃허브의 DNS 는 다음과 같습니다.
1차: 192.30.252.153
2차: 192.30.252.154

DNS서버의 정보는 깃허브의 정책상 변경이 될 수 도 있습니다. 깃페이지의 사용자 도메인을 설정할 때 도움말을 참고하여 확인후에 설정하 하도록 합니다.

A레코드 등록
도메인 등록회사 사이트에서 선택한 도메인의 A레코드 IP를 수정합니다.

 

CNAME  등록
자신의 도메인명 앞에 www를 사용하기 위해서는 추가적으로 CNAME을 등록해 주어야 합니다.