## [2023 공개SW 개발자대회 본선 진행작] 비대면 운동 학습 플랫폼, "MotuS"

### [Check README.md in English]()

## 🫴🏻 Project Introduction

<div align="center">
<p> 이 프로젝트는 비대면 운동 학습 플랫폼 개발을 목적으로 합니다. 
<br/>
<p>누구나 특정 운동에 대한 가이드 영상을 프로그램으로 등록할 수 있으며, 등록된 운동 프로그램을 학습할 수 있습니다. <br/> AI의 유사도 측정을 통해 수행자의 운동 수행 정확도를 확인할 수 있습니다.</p>
<p>특정 도메인에 국한되지 않고, 운동 수행 영상이라면 누구든지 가이드를 등록 및 학습할 수 있다는 것이 프로젝트의 핵심 가치입니다.</p></div>
 <div align="center">
<h3> 비대면 운동 학습 플랫폼, MotuS 입니다. 🌿 </h3>
</div>

## 🏃🏻 MotuS Domain Address
# https://motus.website/

## 🫱🏻‍🫲🏻 H-Five Team ✨

| BE | BE | FE | FE | AI |
| :---: | :---: | :---: | :---: | :---: |
| <img width="130px" src="https://avatars.githubusercontent.com/u/80760160?v=4" /> | <img width="130px" src="https://avatars.githubusercontent.com/u/52206904?v=4"/> |  <img width="130px" src="https://avatars.githubusercontent.com/u/53892427?v=4" /> |  <img width="130px" src="https://avatars.githubusercontent.com/u/35104213?v=4" /> |  <img width="130px" src="https://avatars.githubusercontent.com/u/17959335?v=4" /> |
| 이동헌 | 박주영 | 오소현 | 김경재 | 박인성 |
|한림대학교|한림대학교|한림대학교|한림대학교|한림대학교|
|빅데이터전공 4학년|콘텐츠IT전공 3학년|빅데이터전공 4학년|빅데이터전공 2학년|AI의료융합전공 2학년|
|  [@Dong Heon Lee](https://github.com/Sirius506775)  | [@JuYoung Park](https://github.com/jyp-on) |  [@osohyun0224](https://github.com/osohyun0224)   |  [@PortalCube](https://github.com/PortalCube)     |[@InSung Bahk](https://github.com/insung3511) |


# 💡 MotuS 주요 기능 소개

## 📹 MotuS 플랫폼 사용 설명 영상 Youtube 
- [비대면 운동 학습 플랫폼, MotuS 오픈소스 사용 방법 영상 KOR ](https://www.youtube.com/watch?v=a8xAxw9wZ10&t=21s)
- [Non-face-to-face exercise learning platform, MotuS open source video ENG](https://www.youtube.com/watch?v=zSLehEpCbyw&t=15s)
  
## 1️⃣ **운동 영상 조회**

### 1. 영상 목록
- 현재 서비스에 등록되어 있는 영상들을 영상의 제목, 설명, 썸네일 이미지, 태그와 함께 표시합니다.
  
### 2. 영상 미리보기
- 사용자가 영상을 선택하면 영상의 미리보기와 제목, 설명, 태그가 표시되고 수강 페이지로 이동하는 버튼을 표시합니다.

![모투스_운동상세](https://github.com/MotuS-Web/.github/assets/53892427/a85bef24-d6f6-4637-b93e-3b6aff5bd099)


## 2️⃣ **운동 검색**

### 1. 영상 제목과 태그로 검색
- 영상의 제목과 태그로 검색합니다. 태그로는 특정한 자세의 영상이나, 부위를 선택할 수 있습니다.
![모투스_메인_필터](https://github.com/MotuS-Web/.github/assets/53892427/3e3139bc-f428-4cc1-9afb-70fa957ffb4b)


## 3️⃣ **운동 등록**

### 1. 가이드 영상 등록
- 사용자의 컴퓨터에서 영상을 선택하여 서버로 업로드합니다.
- 업로드한 영상의 스켈레톤 데이터를 AI 서버에서 잘 받아오는 지 확인할 수 있습니다.

### 2. 상세 정보 입력
- 영상의 제목과 설명, 그리고 카테고리 및 자세를 입력합니다.

![모투스_운동등록](https://github.com/MotuS-Web/.github/assets/53892427/326c7c74-0a24-45f1-a850-22e1f99e0ae0)

## 4️⃣ **운동 수강**
### 1. 가이드 영상 재생
- 사용자가 수강할 영상을 재생해서 보여줍니다. 
- 수강할 때 사용자가 운동을 수행하면서 따라해볼 수 있도록 한번 더 재생됩니다.
- 사용자가 원한다면 측정하기 전에 계속해서 돌려볼 수 있습니다.

### 2. 사용자 화면 녹화
- 측정을 시작하면 영상이 재생되는 동안 사용자의 화면을 녹화합니다.
- 영상이 종료되면 녹화를 종료하고 서버로 전송됩니다.

![모투스_운동수강](https://github.com/MotuS-Web/.github/assets/53892427/aa9d421a-a660-4ec0-aad7-ee7d73e559ca)

### 3. 수행유사도 판정
- 사용자의 영상을 AI 서버에서 분석하고, 원본 영상과 얼마나 일치하는지 유사도를 산출하여 표시해줍니다.
- 유사도를 받으면 퍼센트에 따라 Perfect, Great, Good, Bad로 수행 결과를 사용자에게 보여줍니다.

![모투스_운동결과](https://github.com/MotuS-Web/.github/assets/53892427/3cad1f39-4324-465e-9506-3de09fb3a57e)
  

## 📚 MotuS Tech Stacks

| 🫱🏻‍🫲🏻 H-FIVE  Team | 📚 Tech Stacks  |
|:---:|:---:|
| Collaboration Tools|``Github`` ``Slack`` ``Notion``|

## [FrontEnd Repo](https://github.com/MotuS-Web/MotuS-FrontEnd)
|🧑🏻‍💻  FrontEnd  Team | 📚 Tech Stacks  |
|:---:|:---:|
|Dev Packages |``React`` ``Redux`` ``Axios`` |
|Development Support Tools  |``ESLint`` ``Prettier``  ``Vercel`` ``Vite``|
|License|[MotuS Frontend License](https://github.com/MotuS-Web/MotuS-FrontEnd/blob/master/LICENSE) |

## [BackEnd Repo](https://github.com/MotuS-Web/MotuS-Backend)

|🧑🏻‍💻  BackEnd  Team | 📚 Tech Stacks  |
|:---:|:---:|
| Environment |``InteliJ`` ``Postman`` ``Git Action`` ``Git`` ``Gradle`` ``Raspberry Pi 4B`` |
| Development  |``Spring-Boot`` ``Java`` ``NCP(Naver Cloud Platform)`` ``MariaDB``|
|Dependencies| ``QueryDsl`` ``Spring-Data-JPA`` ``Spring Security`` ``JWT(Json Web Token)`` ``Lombok`` ``Validation`` ``Gson``|
|License|[MotuS Backend License](https://github.com/MotuS-Web/MotuS-Backend/blob/main/LICENSE) |

## [AI Repo](https://github.com/MotuS-Web/MotuS-ML)

|🧑🏻‍💻  AI Team | 📚 Tech Stacks  |
|:---:|:---:|
| Frameworks Server | ``FastAPI`` , ``unvicron``, ``mysql`` |
| Frameworks AI  |``Pytorch``, ``Numpy``|
| Frameworks Pre-processing |``Scikit-learn``, ``Scikit-video``|
| Environment |``Macbook Pro M1`` ``GTX 2070 Super`` ``Visual Studio Code`` ``Postman``|
|License|[MotuS AI License](https://github.com/MotuS-Web/MotuS-ML/blob/main/LICENSE) |

## 🧾 MotuS System Architecture

<div align="center">
<img alt="image" width="1000" src="https://github.com/MotuS-Web/.github/assets/80760160/3107fe94-7fe3-4f0f-b299-a8fb83c6561e"/></div>


## 🧾 Fuction Architecture

### 👤 Do Exercise Fuction Architecture

<div align="center">
<img alt="image" width="1000" src="https://github.com/ReHab-Web/.github/assets/53892427/8e09d826-0cf0-4ac7-bdc5-ae4ddb2444e8"/></div>

### 👤🔧 Register Video Fuction Architecture

<div align="center">
<img alt="image" width="1000" src="https://github.com/ReHab-Web/.github/assets/53892427/72a3b816-bc8d-409e-afb9-0099e28968fd"/></div>

## 🧾 Dev Docs.
- [MotuS 기능명세서](https://www.notion.so/opensw-motus/f60f87f72b4849bd985f0d79dabf6802?v=a22a6006cb654ab385a7003be619a86f)
- [MotuS API 명세서](https://www.notion.so/opensw-motus/API-0994cf4364874db398428df3cf1205d0)
- [Developer Kanban board](https://github.com/orgs/MotuS-Web/projects/1)
