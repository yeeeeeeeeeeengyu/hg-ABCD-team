# `ABCD` - `우리동네`

해커그라운드 해커톤에 참여하는 `ABCD` 팀의 `우리동네`입니다.

## 참고 문서

> 아래 두 링크는 해커톤에서 앱을 개발하면서 참고할 만한 문서들입니다. 이 문서들에서 언급한 서비스 이외에도 더 많은 서비스들이 PaaS, SaaS, 서버리스 형태로 제공되니 참고하세요.

- [순한맛](./REFERENCES_BASIC.md)
- [매운맛](./REFERENCES_ADVANCED.md)

## 제품/서비스 소개

<!-- 아래 링크는 지우지 마세요 -->
[제품/서비스 소개 보기](TOPIC.md)
<!-- 위 링크는 지우지 마세요 -->

## 오픈 소스 라이센스

<!-- 아래 링크는 지우지 마세요 -->
[오픈소스 라이센스 보기](./LICENSE)
<!-- 위 링크는 지우지 마세요 -->

## 설치 방법

> **아래 제공하는 설치 방법을 통해 심사위원단이 여러분의 제품/서비스를 실제 Microsoft 애저 클라우드에 배포하고 설치할 수 있어야 합니다. 만약 아래 설치 방법대로 따라해서 배포 및 설치가 되지 않을 경우 본선에 진출할 수 없습니다.**
>
> 0. 깃허브에서 코드를 zip 파일로 다운받은뒤 압축 해제 합니다.
> 1. node.js 설치 https://nodejs.org/en 다음 사이트에 접속하여download node.js LTS 버튼을 눌러 node.js를 다운하고 설치한다.
> 2. 프로젝트 폴더를 vscode로 연뒤 터미널을 켜 npm init 이라는 명령어를 입력한다.


### 사전 준비 사항

> 1. Azure 구독이 되어져 있는 계정 >> 구독은 Visa, MasterCard, American Express로 가능함
> 2. Azure CLI, Azure Powershell >> 리소스 관리를 위해 필요하고, az login 명령어로
> 3. 콘솔에서 Azure에 접근
> 4. Visual Studio Code
> 5. Github 계정 >> Visual Studio Code에서 콘솔로 배포할 때 Github 계정을 사용함
> node.js package 파일 및 프로젝트 파일
> Docker Desktop
> Git

## 시작하기

> 0. Visual Studio Code를 실행하고, 왼쪽 위의 파일(File)을 클릭.
node.js 프로젝트 폴더를 선택 << 내가 배포할 폴더 선택.
> 1. Ctrl + Shift + ` 키를 눌러 터미널을 실행시킴.
> 2. ```cd [현재 디렉토리]``` 실행, 현재 디렉토리로 이동.
> 3. ```az login``` 실행 후, MS 계정 로그인
>    ※간혹 로그인이 되지 않을 때가 있는데, 이는 tenant 오류. 위의 노란색 글씨의 warning 글씨 중 'tenant '...'' 를 복사해 ```az login --tenant ...``` 실행
> 4. ```azd auth login``` 실행 후, MS 계정 로그인
> 5. 터미널 창 오른쪽 위 + 옆 아래화살표를 눌러 Git Bash 선택
> 6. ```GITHUB_TOKEN=```
     ```gh auth login``` 실행 후
Github.com
>
> HTTPS
> Yes
> Login with a browser
> 순으로 실행
> 이후 나오는 8자리 코드 숙지 후 Enter 입력
> 브라우저에서 깃허브 로그인, 8자리 코드 입력
> 
> ```select environment...``` 창이 뜰 때, 미리 있던 Azure 리소스 그룹 이름 넣기
> ※'rg-'는 이미 할당되어 있기 때문에 생략할 것
>
> ```azd init``` 입력 후 ERROR 메시지에서 리소스 그룹 할당 되어있는지 확인하기
> Visual Studio Code 왼쪽 파일 탐색기에서 .yaml 파일, .env 파일이 보인다면
> ```azd up``` 실행 후 깔려있던 Docker Desktop 실행
> Endpoint가 나오면 배포 끝 ~
