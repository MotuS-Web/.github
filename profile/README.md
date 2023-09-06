## [2023 공개SW 개발자대회 출품작] 비대면 운동 학습 플랫폼, "Re:Hab"

## 🫴🏻 Project Introduction

<div align="left">
<p> 이 프로젝트는 비대면 운동 학습 플랫폼 개발을 목적으로 한다. 
<br/>
<p>관리자는 특정 운동에 대한 가이드 영상을 프로그램으로 등록할 수 있으며, 사용자는 등록된 운동 프로그램을 학습하는 과정에서, AI의 유사도 측정을 통해 개인의 운동 수행 정확도를 확인할 수 있다.</p>
<p>특정 도메인에 국한되지 않고, 운동 수행 영상이라면 누구든지 가이드를 등록 및 학습할 수 있다는 것이 프로젝트의 핵심 가치이다.</p></div>
 <div align="center">
<h3> 비대면 운동 학습 플랫폼, Re:Hab 입니다. 🌿 </h3>
</div>

## 🫱🏻‍🫲🏻 H-Five Team ✨

| BE | BE | FE | FE | AI |
| :---: | :---: | :---: | :---: | :---: |
| <img width="130px" src="https://avatars.githubusercontent.com/u/80760160?v=4" /> | <img width="130px" src="https://avatars.githubusercontent.com/u/52206904?v=4"/> |  <img width="130px" src="https://avatars.githubusercontent.com/u/53892427?v=4" /> |  <img width="130px" src="https://avatars.githubusercontent.com/u/35104213?v=4" /> |  <img width="130px" src="https://avatars.githubusercontent.com/u/17959335?v=4" /> |
| 이동헌 | 박주영 | 오소현 | 김경재 | 박인성 |
|  [@Dong Heon Lee](https://github.com/Sirius506775)  | [@JuYoung Park](https://github.com/jyp-on) |  [@osohyun0224](https://github.com/osohyun0224)   |  [@PortalCube](https://github.com/PortalCube)     |[@InSung Bahk](https://github.com/insung3511) |


## 💡 Re:Hab 주요 기능 소개

### 1️⃣ **운동 강의 학습**
 
- 강의 수강 : 자신이 원하는 운동 강의를 선택 후 수강하며 운동을 진행.
- AI 유사도 판정 : 동작에 대해 올바른 자세로 운동을 진행했는지 가이드영상를 바탕으로 동작 유사도를 판정.
- 높은 유사도 유도: 높은 유사도를 받을 때까지 사용자의 반복적인 수강을 도와 효과적인 운동을 도움.


### 🤔 Case 1: 올바른 자세로 수강 시 

<div align="center">
<img alt="image" width="600" src="https://github.com/ReHab-Web/.github/assets/53892427/b52f2a22-7d6e-4cf5-b799-901171b3473b"/></div>

- 😀 높은 정확도로 판정됨

<div align="center">
<img alt="image" width="600" src="https://github.com/ReHab-Web/.github/assets/53892427/39938578-66da-4ace-bdd0-b3155e2646de"/></div>

### 🤔 Case 2: 나쁜 자세로 수강 시

<div align="center">
<img alt="image" width="600" src="https://github.com/ReHab-Web/.github/assets/53892427/605d4741-2943-4307-9a3d-22b56af3ec5c"/></div>

- 😥 낮은 정확도로 판정됨
  
<div align="center">
<img alt="image" width="600" src="https://github.com/ReHab-Web/.github/assets/53892427/047e1a2a-ee6c-4b79-aeff-60f6869d3d88"/></div>


<br/><br/>
### 2️⃣ **운동 강의 등록**

- 관리자(admin)은 사용자들이 수강할 운동 프로그램을 직접 생성할 수 있음.
- 가이드 영상과 프로그램 제목, 설명, 태그를 설정해 프로그램을 등록함.
  
<div align="center">
<img alt="image" width="600" src="https://github.com/ReHab-Web/.github/assets/53892427/69b55330-5412-4ee2-8549-6333d15b7d1b"/>
</div>

## 📚 Re:Hab Tech Stacks

### 개발 기간⏳
#### 2023. 07.19 ~ 2023. 09. 07 

### 🫱🏻‍🫲🏻🧑🏻‍💻 Development Collaboration Tools
``Github`` ``Slack`` ``Notion``

### 🧑🏻‍💻 FrontEnd Team

#### Dev Packages: 
``React`` ``Redux`` ``Axios``

#### Development Support Tools 
``ESLint`` ``Prettier``  ``Vercel`` ``Vite``

### 🧑🏻‍💻 BackEnd Team

#### Environment
``InteliJ`` ``Postman`` ``Git Action`` ``Git`` ``Gradle`` ``Raspberry Pi 4B``

#### Development
``Spring-Boot`` ``Java`` ``NCP(Naver Cloud Platform)`` ``MariaDB``
  
#### Dependencies
``QueryDsl`` ``Spring-Data-JPA`` ``Spring Security`` ``JWT(Json Web Token)`` ``Lombok`` ``Validation`` ``Gson``

### 🧑🏻‍💻 AI Team

#### Languages
``Python``
  
#### Frameworks
- Server: ``FastAPI`` , ``unvicron``, ``mysql``
- AI : ``Pytorch``, ``Numpy``
- Pre-processing: ``Scikit-learn``, ``Scikit-video``
  
#### Environment
``Macbook Pro M1`` ``GTX 2070 Super`` ``Visual Studio Code`` ``Postman``
  
## 🧾 System Architecture

<div align="center">
<img alt="image" width="1000" src="https://github.com/ReHab-Web/.github/assets/53892427/d4444956-312b-43c9-89fc-8ed3ceee23d6"/></div>

## 🧾 Fuction Architecture

### 👤 Client Fuction Architecture

<div align="center">
<img alt="image" width="1000" src="https://github.com/ReHab-Web/.github/assets/53892427/8e09d826-0cf0-4ac7-bdc5-ae4ddb2444e8"/></div>

### 👤🔧 Admin Fuction Architecture

<div align="center">
<img alt="image" width="1000" src="https://github.com/ReHab-Web/.github/assets/53892427/72a3b816-bc8d-409e-afb9-0099e28968fd"/></div>
