# BE10-2nd-4Team

## 4getMoney
<br />

![Image](https://github.com/user-attachments/assets/712ad54b-acec-4697-8fa6-039629303a1a)

<br />
<br />

## 📆 프로젝트 기간

- 2025.06.17 - 2025.06.19

<br />

## 깃 주소 Link. https://github.com/EDDI-RobotAcademy/4getMoney

## 노션 주소 Link. https://www.notion.so/214bbd1e85b180a8ba90f3d634655468?v=214bbd1e85b18088b3b7000cab4c9fec

<br />

## 📖 주요 기능

### 1.React를 사용한 개발로 Virtual DOM 기반의 빠른 렌더링을 구현하였고 수많은 오픈소스 컴포넌트와 라이브러리 사용

### 2.Micro Frontends(MFE)로 개발하여 팀원간 개발의 분업화 효율을 늘려 다양한 기능을 동시 개발하는 효율을 증대

### 3.TypeScript를 사용하여 정적 타입지정을 통해 컴파일 단계에서 오류를 포착하고 명시적인 정적 타입 지정은 개발자의 의도를 명확하게 알수 있게 코드를 기술함

<br />
<br />

## 🛠 기술 스택

<div align=left>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"> 
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <br>
  <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white">
  <img src="https://img.shields.io/badge/recoil-100000?style=for-the-badge&logo=recoil&logoColor=white">
  <img src="https://img.shields.io/badge/kakao_login-FFCD00?style=for-the-badge&logo=kakao&logoColor=white">
  <img src="https://img.shields.io/badge/google_login-4285F4?style=for-the-badge&logo=google&logoColor=white">




  
</div>
<br>
<br>

## 🔥 트러블 슈팅

<br />
 <details> <summary>➡️드롭다운 2열이 한꺼번에 열리는 상황. 클릭한 드롭다운 탭만 작동하게 구현을 하였으나, 옆 탭도 같이 열리는 상황이 발생.</summary> <div markdown="1">
  <br/>
   
**`해결방안`**
 *2시간이 넘는 변경 작업을 진행하였으나 원하는 형태로 드롭다운이 되지 않게 되어 1열로 변경하여 드롭다운 구현
   </div>
  </details>
  

 <details> <summary>➡️이미지가 보이지 않는 상황. 이미지를 .png파일로 만들어서 입력하려 했는데 화면에 이미지가 출력되지 않음.</summary> <div markdown="1">
  <br/>
   
 **`해결방안`**<br/>
  *img src="http://localhost:3002/samsung.png"  이런 식으로 경로를 만들어서 대입하니 정상 출력됨.
    </div>
  </details>
  
 <details> <summary>➡️소셜로그인을 하기위해 clinet id값을 .env에 설정하고 통신을 연결 하려고 하였으나 .env를 찾지 못해 실패함.</summary> <div markdown="1">
  <br/>
   
 **`해결방안`**<br/>
  *rspack.config.ts 파일에 DefinePlugin을 추가하여 카카오와 구글에 대한 환경 변수 사용을 가능하게 수정함.
   </div>
  </details>
  
 <details> <summary>➡️로그인후 프로필 이미지를 눌러서 유저메뉴 모달창을 구현. 로그아웃후 재 로그인시 모달창이 열려 있는 상태로 로그인이 됨.</summary> <div markdown="1">
  <br/>
   
**`해결방안`**<br/>
  *유저 메뉴 모달창에서 로그아웃 버튼이 있어 로그아웃을 실행시 그 핸들에 모달창 상태값을 false로 넣어주어 상태값 초기화(초기값이 false)를 시켜줌으로 해결
    </div>
  </details>

<br />
<br />

<details> <summary> ## ➡️페이지 작동 모습</summary> <div markdown="1">
 
<img width="1886" height="907" alt="Image" src="https://github.com/user-attachments/assets/c8f42608-36e3-496e-a895-6258f8d9e9e4" />

<img width="1737" height="867" alt="Image" src="https://github.com/user-attachments/assets/2157620b-feb7-4bf7-96d0-2a344418a292" />

<img width="1742" height="871" alt="Image" src="https://github.com/user-attachments/assets/64fda700-d3f2-43c4-b3ce-9b80ce0f3d4f" />

<img width="1896" height="883" alt="Image" src="https://github.com/user-attachments/assets/25d8aaa9-d6b2-4592-bc46-b432fddfa3f6" />

<img width="1098" height="829" alt="Image" src="https://github.com/user-attachments/assets/5168860e-a54c-471b-9c53-e49276a01fce" />

<img width="1253" height="855" alt="Image" src="https://github.com/user-attachments/assets/b5b3485d-54bc-47bb-b773-17c6aa7f6df2" />

<img width="1178" height="791" alt="Image" src="https://github.com/user-attachments/assets/876a2f5c-d112-492e-90d8-774a11f4e765" />

<img width="1088" height="857" alt="Image" src="https://github.com/user-attachments/assets/e2c89b5e-0528-40a0-ad7b-cf634d724bdc" />

<img width="1028" height="831" alt="Image" src="https://github.com/user-attachments/assets/37821547-e17d-40c8-8b35-645ae340cc8d" />

<img width="1067" height="886" alt="Image" src="https://github.com/user-attachments/assets/99b5cf0a-79e9-46ab-b909-e615933e9e23" />

<img width="1027" height="873" alt="Image" src="https://github.com/user-attachments/assets/ea6180c7-74c2-4dcd-8d4f-5b14fba96294" />

<img width="1435" height="831" alt="Image" src="https://github.com/user-attachments/assets/0bcf4e8c-1c3e-44a5-a47c-556fdf149eeb" />

<img width="1265" height="834" alt="Image" src="https://github.com/user-attachments/assets/82509afa-2be0-4e6e-b255-6e3e69a873c8" />

 </div>
  </details>

<br />
<br />

## 😎 팀원

<table>
   <tr>
    <td align="center"><b><a href="https://github.com/unchul">임운철</a></b></td>
    <td align="center"><b><a href="https://github.com/Roto90-BackEnd">박태준</a></b></td>
    <td align="center"><b><a href="https://github.com/kim-jeongbeom">김정범</a></b></td>
    <td align="center"><b><a href="https://github.com/Juyoung-LEE1215">이주영</a></b></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/unchul"><img src="https://avatars.githubusercontent.com/u/105141025?v=4" width="100px" /></a></td>
    <td align="center"><a href="https://github.com/Roto90-BackEnd"><img src="https://avatars.githubusercontent.com/u/207959016?v=4" width="100px" /></a></td>
    <td align="center"><a href="https://github.com/kim-jeongbeom"><img src="https://avatars.githubusercontent.com/u/205934808?v=4" width="100px" /></a></td>  
    <td align="center"><a href="https://github.com/Juyoung-LEE1215"><img src="https://avatars.githubusercontent.com/u/207958971?v=4" width="100px" /></a></td>  
  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td align="center"><b>Frontend</b></td>
    <td align="center"><b>Frontend</b></td>
    <td align="center"><b>Frontend</b></td>
  </tr>
