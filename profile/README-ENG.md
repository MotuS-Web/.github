## [2023 OpenSW Developer Contest Main Round Progress] Non-Face-to-Face Exercise Learning Platform, "MotuS"

### [Check README.md in Korean](https://github.com/MotuS-Web/.github/blob/main/profile/README.md)

## 🫴🏻 Project Introduction

<div align="center">
<p>This project aims to develop a non-face-to-face exercise learning platform. 
<br/>
<p>Anyone can register a guide video for a specific exercise on the platform, and learners can access the registered exercise programs. Through AI's similarity measurement, users can check the accuracy of their exercise performance.</p>
<p>The core value of the project is that it is not limited to a specific domain, and if there is an exercise performance video, anyone can register and learn from the guide.</p></div>
 <div align="center">
<h3> Welcome to the non-face-to-face exercise learning platform, MotuS. 🌿 </h3>
</div>

## 🏃🏻 MotuS Domain Address
# https://motus.website/

## 🫱🏻‍🫲🏻 H-Five Team ✨

| BE | BE | FE | FE | AI |
| :---: | :---: | :---: | :---: | :---: |
| <img width="130px" src="https://avatars.githubusercontent.com/u/80760160?v=4" /> | <img width="130px" src="https://avatars.githubusercontent.com/u/52206904?v=4"/> |  <img width="130px" src="https://avatars.githubusercontent.com/u/53892427?v=4" /> |  <img width="130px" src="https://avatars.githubusercontent.com/u/35104213?v=4" /> |  <img width="130px" src="https://avatars.githubusercontent.com/u/17959335?v=4" /> |
| DongHun Lee | JuYoung Park | SoHyun Oh | KyungJae kim | InSung Park |
|Hallym University|Hallym University|Hallym University|Hallym University|Hallym University|
|Computer Engineering 4th|Computer Engineering 3th|Computer Engineering 4th|Computer Engineering 2th|Artificial Intelligence 2th|
|  [@Dong Heon Lee](https://github.com/Sirius506775)  | [@JuYoung Park](https://github.com/jyp-on) |  [@osohyun0224](https://github.com/osohyun0224)   |  [@PortalCube](https://github.com/PortalCube)     |[@InSung Bahk](https://github.com/insung3511) |


# 💡  Key Features of MotuS

## 📹 MotuS Platform Tutorial Videos
- [Non-face-to-face exercise learning platform, MotuS open source video KOR](https://www.youtube.com/watch?v=a8xAxw9wZ10&t=21s)
- [Non-face-to-face exercise learning platform, MotuS open source video ENG](https://www.youtube.com/watch?v=zSLehEpCbyw&t=15s)
  
## 1️⃣ Exercise Video Browsing

### 1. Video List
- Videos currently registered in the service are displayed with their titles, descriptions, thumbnail images, and tags.
  
### 2. Video Preview
- When a user selects a video, a preview of the video along with the title, description, and tags are shown, along with a button to move to the course page.

![모투스_운동상세](https://github.com/MotuS-Web/.github/assets/53892427/a85bef24-d6f6-4637-b93e-3b6aff5bd099)


## 2️⃣ Exercise Search

### 1. Search by Video Title and Tags
- Users can search by video title and tags. Tags allow users to select specific postures or body parts.
  
![모투스_메인_필터](https://github.com/MotuS-Web/.github/assets/53892427/3e3139bc-f428-4cc1-9afb-70fa957ffb4b)


## 3️⃣ Exercise Registration

### 1. Register Guide Video
- Users can select a video from their computer to upload to the server.
- You can check whether the AI server receives the skeleton data of the uploaded video properly.

### 2. Enter Detailed Information
- Users can enter the title, description, category, and posture of the video.

![모투스_운동등록](https://github.com/MotuS-Web/.github/assets/53892427/326c7c74-0a24-45f1-a850-22e1f99e0ae0)

## 4️⃣ Taking the Exercise Course
### 1. Play the Guide Video
- The video that the user wants to take is played for them to see.
- The video is played again for users to follow along while performing the exercise.
- If the user wishes, they can repeatedly view the video before the measurement.

### 2. Record User's Screen
- When the measurement starts, the user's screen is recorded while the video is playing.
- When the video ends, the recording stops and is sent to the server.

![모투스_운동수강](https://github.com/MotuS-Web/.github/assets/53892427/aa9d421a-a660-4ec0-aad7-ee7d73e559ca)

### 3. Performance Similarity Judgment
- The user's video is analyzed on the AI server, and the similarity to the original video is calculated and displayed.
- Depending on the similarity score, the performance results are displayed to the user as Perfect, Great, Good, or Bad.

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
- [MotuS Functional Specification](https://www.notion.so/opensw-motus/f60f87f72b4849bd985f0d79dabf6802?v=a22a6006cb654ab385a7003be619a86f)
- [MotuS API Specification](https://www.notion.so/opensw-motus/API-0994cf4364874db398428df3cf1205d0)
- [Developer Kanban board](https://github.com/orgs/MotuS-Web/projects/1)
