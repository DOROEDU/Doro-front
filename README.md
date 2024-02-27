# 도로 강사 관리 애플리케이션 - DORO EDU APP

<div align="center"><br/>

  <img width="250px" src="https://github.com/DOROEDU/Doro-Front/assets/42240254/4d858d31-b028-4862-b4e4-bb193b6c6d06" /> 

</div>
<br/>

## 🚀 배포 주소 🚀

> **안드로이드** : [https://play.google.com/store/apps/details?id=com.doro.android&hl=ko-KR](https://play.google.com/store/apps/details?id=com.doro.android&hl=ko-KR) <br>
> **IOS** : [https://apps.apple.com/kr/app/doro-edu/id6450978098](https://apps.apple.com/kr/app/doro-edu/id6450978098) <br>
<br/>

## 📱 애플리케이션 개발팀 📱

|          김민혁          |          노세인          |                                                                                                     
| :------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: |
|   <img width="160px" src="https://avatars.githubusercontent.com/u/42240254?v=4" />    |                      <img width="160px" src="https://avatars.githubusercontent.com/u/71018440?v=4" />    |
|   [@Minhyeok Kim](https://github.com/jaqwe2301)   |   [@sein](https://github.com/dslov89)   |
<br/>

## 📘 프로젝트 소개 📘

도로는 초중고 등의 교육 기관과 대학생 전문 강사를 매칭하는 역할을 하는 기업입니다.<br/><br/>
DORO EDU APP은 강의 신청 및 관리를 위해 기존에 노션, 디스코드, 구글폼 등 여러 플랫폼을 이용해야 했던 번거로움을 해소하고, 이를 한 곳에서 관리할 수 있도록 만들어진 애플리케이션입니다.
<br/><br/>
주요 기능은 다음과 같습니다.<br/><br/>

1. 교육 프로그램 신청 폼: 사용자가 RODU에서 제공하는 다양한 교육 프로그램에 신청할 수 있는 간편한 온라인 폼입니다.<br/>
2. 문의 게시판: 사용자와 RODU 간의 원활한 커뮤니케이션을 지원하는 인터페이스로, 질문을 게시하고 답변을 받을 수 있습니다.<br/>
3. 교육 컨텐츠 소개: RODU에서 제공하는 교육 컨텐츠와 관련 정보를 사용자에게 소개하며, 교육의 질을 향상시키는 데 기여합니다.<br/><br/>

---

## 🛠️ Stacks 🛠️

### Environment
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)             

### Config
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)        

### Development
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Recoil](https://img.shields.io/badge/Recoil-F2F2F2?style=for-the-badge&logo=Recoil&logoColor=3578E5)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-0F1729?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4)

### Hosting & Deployment
![Netlify](https://img.shields.io/badge/netlify-333333?style=for-the-badge&logo=netlify&logoColor=00C7B7)

---
## 화면 구성 📺
|  **메인 페이지**  |  **교육 컨텐츠 페이지**  |
| :-------------------------------------------: | :------------: |
| <img width="329" src="https://github.com/RODU-LAB/FrontEnd-Web/assets/42240254/4b9521b2-122a-4c1f-86ca-b7438fd03e52"/> |  <img width="329" src="https://github.com/RODU-LAB/FrontEnd-Web/assets/42240254/44d13da2-c612-4456-acfb-ae44be5f39f0"/>|  
| **교육 신청 페이지**   |  **문의 게시판 페이지**   |  
| <img width="329" src="https://github.com/RODU-LAB/FrontEnd-Web/assets/42240254/c332730d-069d-4385-8572-340aebdae8f7"/>   |  <img width="329" src="https://github.com/RODU-LAB/FrontEnd-Web/assets/42240254/29b2fd88-739c-4cba-b487-9fc3d9092c5e"/>     |

---
## 📦 주요 기술 📦

### ⭐️ 반응형 웹 서비스 (진행 중)
- 사용성과 접근성을 크게 향상시켜 사용자 경험을 최적화

### ⭐️ 상태 관리 라이브러리, Recoil
- 한 번의 카카오톡 인증을 통해 발급받은 토큰을 Recoil에 저장함으로써, 교육 신청과 문의 게시판 이용 시 여러 번의 인증 과정 없이 서비스 이용
- 작성 중인 폼의 내용을 Recoil에 임시 저장함으로써, 폼 재작성 시에 저장된 내용을 불러와 이어서 작성

### ⭐️ JWT 토큰을 활용한 로그인 구현
- JWT 토큰을 localStorage와 sessionStorage에 저장하여 관리자 로그인 세션을 관리
- 주로 교육 신청 내역 확인 및 문의 게시판 답변에 사용

### ⭐️ RestFullAPI를 통한 백엔드와 협업
- 교육 신청 폼 데이터 전달 및 내역 조회
- 문의 게시글 등록·삭제·수정, 답변·삭제(관리자 기능)
- 관리자 로그인
- 카카오톡 인증

---
