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
0. 깃허브에서 CODE 버튼을 누른 후 ZIP DOWNLOAD 버튼을 눌러 다운로드를 시작합니다.![스크린샷 2024-08-26 235554](https://github.com/user-attachments/assets/5e6681c4-4902-4150-9809-a78cf19830a4)
> 
0-1. 다운로드된 ZIP 파일은 '파일 탐색기' 앱의 '다운로드' 폴더 안에 있습니다.![스크린샷 2024-08-27 000149](https://github.com/user-attachments/assets/a3f895b3-dea5-4390-9978-8bfdca4834a3)


0-2. ZIP 파일을 바탕 화면으로 옮기고, '압축 풀기'를 실행합니다.
![스크린샷 2024-08-27 002210](https://github.com/user-attachments/assets/41f0a6cf-7dc3-46d2-b928-34a3a0ae6a8e)

![스크린샷 2024-08-27 002250](https://github.com/user-attachments/assets/ef3183fb-7247-484a-9a87-8fdc35868ff2)
> ※ '압축 풀기'는 ZIP파일을 우클릭 해야 보입니다.
![스크린샷 2024-08-27 002442](https://github.com/user-attachments/assets/a2b16bd7-fe3d-4032-9bf0-d3e095270af1)

0-3. 압축이 풀린 파일을 열어 안의 같은 이름인 파일을 바탕 화면으로 끌어내립니다.
![스크린샷 2024-08-27 002605](https://github.com/user-attachments/assets/96151928-5b65-40c1-bbd0-d487d52bae9b)

![스크린샷 2024-08-27 002756](https://github.com/user-attachments/assets/6531bcb9-87f6-48a3-9584-2f11b289ea06)
> ※위 사진처럼 파일이 보인다면 성공입니다~

1. https://nodejs.org/en 사이트에 접속하여 'Download Node.js LTS' 버튼을 눌러 node.js를 다운로드받고 .msi 파일을 실행한다.![SADdsa](https://github.com/user-attachments/assets/59e00b38-1955-4c45-bcc6-3b0fa298b467)
> 
![스크린샷 2024-08-27 000432](https://github.com/user-attachments/assets/9acfe53c-7f0d-4d2e-982d-72ffcec87808)
>
> ※ 두 번째 Agreement 동의서도 함께 웬만하면 Next를 눌러 넘어가도록 한다.
>
![스크린샷 2024-08-27 000816](https://github.com/user-attachments/assets/138ac188-6bb7-4cc6-9a69-f3b870052bed)
>
2. Visual Studio Code를 실행시킨다. ![스크린샷 2024-08-27 001545](https://github.com/user-attachments/assets/204071fa-778b-4b92-a158-f3fc438bb02e)
>
3. Visual Studio Code 창 왼쪽 위의 파일(F) 버튼을 누르고, 폴더 열기... 를 선택한다. ![스크린샷 2024-08-27 001904](https://github.com/user-attachments/assets/de24beff-00d4-49a5-9569-800fc2f1303d)

4. 바탕 화면 폴더를 선택하고, 압축을 풀었던 파일을 선택한다.

   ![스크린샷 2024-08-27 003024](https://github.com/user-attachments/assets/a03d08b5-af98-4a76-b7cd-06370d7993a9)

   ![스크린샷 2024-08-27 003110](https://github.com/user-attachments/assets/1f12937f-97a5-44bc-a963-7f514d93ca69)
   ※ Visual Studio Code ( 이하 VSC ) 탐색기가 이렇게 변하면 성공~

### 사전 준비 사항

1. Azure 구독이 되어져 있는 계정 >> 구독은 Visa, MasterCard, American Express로 가능함
2. Azure CLI, Azure Powershell >> 리소스 관리를 위해 필요하고, az login 명령어로
3. 콘솔에서 Azure에 접근
4. Visual Studio Code
5. Github 계정 >> Visual Studio Code에서 콘솔로 배포할 때 Github 계정을 사용함
6. node.js package 파일 및 프로젝트 파일
7. Docker Desktop
8. Git

## 시작하기
1. Ctrl + Shift + ` 키를 눌러 터미널을 실행시킴.

![스크린샷 2024-08-27 003419](https://github.com/user-attachments/assets/e92c72c9-983d-475e-9975-5898cbac52e3)
 ※키보드 Ctrl + Shift + `  (<< ' 아님) 을 꼭 동시에 누르지는 않아도 된다.

![스크린샷 2024-08-27 003842](https://github.com/user-attachments/assets/c62ebd82-ce13-40fc-a2aa-af36a8f4826b)
 터미널에서 이런 경로가 보이면 성공~


2. ```az login``` 실행 후, MS 계정 로그인

![스크린샷 2024-08-27 004016](https://github.com/user-attachments/assets/dec13863-fa96-4232-967d-9032ee52cd0f)

![스크린샷 2024-08-27 004146](https://github.com/user-attachments/assets/e9706824-1cb4-4d00-a684-b08c0522473c)

>   ※간혹 로그인이 되지 않을 때가 있는데, 이는 tenant 오류. 위의 노란색 글씨의 warning 글씨 중 ```tenant '...'``` 를 복사해 ```az login --tenant ...``` 실행

![스크린샷 2024-08-27 004318](https://github.com/user-attachments/assets/93757e31-c146-4c6a-9ffc-023286bb6e1e)

정상적으로 로그인이 되었다면,
![image](https://github.com/user-attachments/assets/4a3574fa-c7e9-46ed-bccd-d98130a80aed)
이런 화면이 나오는데, Enter 한번 입력하고 az login을 마무리한다.

3. ```azd auth login``` 실행 후, MS 계정 로그인

![스크린샷 2024-08-27 004755](https://github.com/user-attachments/assets/66428576-6052-472e-845b-2bba9305216d)

Visual Studio Code 터미널에 'Logged in th Azure.' 라는 메시지가 출력되면 성공~
5. 터미널 창 오른쪽 위 + 옆 아래화살표를 눌러 Git Bash 선택

![스크린샷 2024-08-27 013741](https://github.com/user-attachments/assets/3dafe63c-6f13-4fc6-95d6-7ded759ebb52)

6. Git Bash 터미널에
   ```GITHUB_TOKEN=```
   ```gh auth login``` 실행 후

![스크린샷 2024-08-27 013935](https://github.com/user-attachments/assets/4a94c212-318a-46fe-9e84-68a458826440)

 Github.com
 HTTPS
 Yes
 Login with a browser
 순으로 입력

![스크린샷 2024-08-27 014100](https://github.com/user-attachments/assets/83d64208-2eca-4382-8248-1bcfc3f025bb)

 이후 나오는 8자리 코드 숙지 후 Enter 입력
 브라우저에서 깃허브 로그인, 8자리 코드 입력
 
 ![스크린샷 2024-08-27 014409](https://github.com/user-attachments/assets/6a1f1557-f80a-4358-be81-f5ec607a6ed0)

 ※ 2차 인증으로 Github Mobile에서 인증하라고 할때는, 
 
 ![스크린샷 2024-08-27 014617](https://github.com/user-attachments/assets/a242f763-8222-4cef-8d2f-fb2cd38c759e)

![스크린샷 2024-08-27 015329](https://github.com/user-attachments/assets/a7fd3c47-745f-4eaf-bb73-5b0d2b1359af)
Github Mobile 앱 키면 바로 인증번호 누르는 창이 뜸

6-1. Github 로그인 후 터미널 창 오른쪽 위 + 옆 아래화살표를 눌러 Powershell 선택

![스크린샷 2024-08-27 022218](https://github.com/user-attachments/assets/1041c198-520a-403d-857b-9980a3fe57e8)

7.  ```azd init``` 입력 후 초기 설정 정의하기
 
![스크린샷 2024-08-27 020107](https://github.com/user-attachments/assets/f9b2136b-ac38-4a8b-bd5a-a972da03fb8d)

![스크린샷 2024-08-27 020203](https://github.com/user-attachments/assets/5dbe7534-6d22-4929-b114-0285c75f0306)

 ![스크린샷 2024-08-27 020309](https://github.com/user-attachments/assets/931fda6d-22ba-4417-98d4-bbb69133259e)

8.  ```select environment...``` 창이 뜰 때, 미리 있던 Azure Portal 리소스 그룹 이름 넣기
> ※'hg-'는 이미 할당되어 있기 때문에 생략할 것

모든 초기 설정이 완료되면

![image](https://github.com/user-attachments/assets/60c50e99-81ed-4de9-bb61-0fea758e43b7)

이런 메시지가 출력된다.
이거 나오면 성공~


 9. Docker Desktop 실행해놓기

     ![스크린샷 2024-08-27 020716](https://github.com/user-attachments/assets/7165b6a5-4846-4bdc-aa16-5d5370fbe1b4)

 10. ```azd up``` 실행 후 기다리면 배포 성공~

첫 실행 시 Azure Subscribtion과 Azure location을 고르라는 말이 출력되는데, 자기가 구독되어있는 애저와 koreacentral 지역을 고르면 된다
![image](https://github.com/user-attachments/assets/10ade0e6-7582-495a-928e-9765215bdc6b)


※ 터미널에 출력되는 Endpoint가 정상적으로 작동되면 배포에 성공했다는 뜻이다

![image](https://github.com/user-attachments/assets/04107feb-87cb-41ee-9ac5-2fb1cac1a024)

>> 다른사람 컴퓨터에서 이 링크를 실행해도 똑같은 화면이 나온다

끝 ~ 
