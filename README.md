<img src="https://github.com/user-attachments/assets/89211c25-b1b3-4326-b706-65671a361153"/>

## 멤버
2024-07-25 ~

<table>
  <tr>
   <td><img src="https://github.com/iris-starry.png" width="120px"/><br/><a href="https://github.com/iris-starry">FE 김선희</a></td>
   <td><img src="https://github.com/wlgus123.png" width="120px"/><br/><a href="https://github.com/wlgus123">FE 김지현</a></td>
   <td><img src="https://github.com/dlwlstjs.png" width="120px"/><br/><a href="https://github.com/dlwlstjs">FE 이진선</a></td>
   <td><img src="https://github.com/hyeseung12.png" width="120px"/><br/><a href="https://github.com/hyeseung12">BE 김혜승</a></td>
   <td><img src="https://github.com/darecoco.png" width="120px"/><br/><a href="https://github.com/darecoco">BE 이지인</a></td>
  </tr>
</table>
<br>

## 프로젝트 사용 기술

<img src="https://github.com/user-attachments/assets/9a1aecb0-e165-49b4-b9a3-5b0845140afd" />
<br><br>

## 프로젝트 폴더 구조

```
폴더 구조 작성 cmd 명령어 : 'tree > level.txt' 
```

```
└─src
    ├─main
    │  ├─kotlin
    │  │  └─kr
    │  │      └─hs
    │  │          └─study
    │  │              └─codeusbackend
    │  └─resources
    │      ├─static
    │      └─templates
    └─test
        └─kotlin
            └─kr
                └─hs
                    └─study
                        └─codeusbackend
```
<br>

## 기여 방법

기여를 원하시는 분들은 먼저 이슈를 등록해 주세요. 그 후, fork한 저장소에서 작업한 후 풀 리퀘스트를 보내주시면 됩니다.
<br><br>

## 런타임 구동

### 1. 저장소 클론

먼저, GitHub 저장소를 로컬에 복제합니다.

```
git clone https://github.com/CODE-U-S/CodeUS-Backend.git
cd CodeUS-Backend
```

### 2. dependency 설치

루트 디렉토리에서 모든 dependecy를 다운받습니다.

<img width="1919" alt="스크린샷 2024-07-26 081402" src="https://github.com/user-attachments/assets/c978132c-7b45-4f0a-9083-03f5fd7d1fc9">

### 3. 백엔드 실행

백엔드 실행 시, application.yml에서 필요한 환경 변수를 설정해야 합니다. [설정하는 방법](https://foregoing-session-2ae.notion.site/a57d70130bd34b31ae953094673bec1a?pvs=4)

백엔드 서버는 기본적으로 http://localhost:8080 에서 실행됩니다.

Environment variables는 다음과 같습니다.

```
DB_HOST=;DB_PORT=;DB_NAME=;DB_USERNAME=;DB_PASSWORD=;REDIS_HOST=;REDIS_PORT=;DDL_AUTO=;JWT_SECRET=;
```
<br>

## Commit Convention

<table>
  <tr>
    <td width="500px">value</td>
    <td width="1500px">meaning</td>
  </tr>
  <tr>
    <td>feat</td>
    <td>새로운 기능 추가</td>
  </tr>
  <tr>
    <td>add</td>
    <td>새로운 클래스 추가</td>
  </tr>
  <tr>
    <td>fix</td>
    <td>버그 수정</td>
  </tr>
  <tr>
    <td>docs</td>
    <td>문서 변경</td>
  </tr>
  <tr>
    <td>refactor</td>
    <td>리팩토링</td>
  </tr>
  <tr>
    <td>move</td>
    <td>파일 또는 폴더 이동</td>
  </tr>
  <tr>
    <td>test</td>
    <td>테스트 관련 사항</td>
  </tr>
  <tr>
    <td>chore</td>
    <td>기타</td>
  </tr>
</table>
<br>

## 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다. 자세한 내용은 LICENSE 파일을 참조하세요.

```
위의 README 파일은 프로젝트에 대한 전반적인 정보를 포함하고 있습니다. 자신의 프로젝트에 맞게 내용을 수정하여 사용하면 됩니다. 이 파일을 프로젝트의 루트 디렉토리에 `README.md` 파일로 저장하면 됩니다.
```
