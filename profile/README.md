# **십이지신으로 보는 운세**


[http://ec2-3-38-109-64.ap-northeast-2.compute.amazonaws.com/](http://ec2-3-38-109-64.ap-northeast-2.compute.amazonaws.com/)



사용자의 얼굴 이미지를 분석해 닮은 십이지신을 알려주는 서비스

<p align="center">
<img src = "https://user-images.githubusercontent.com/87285536/193127614-a3ef1d62-ced6-4a48-a728-26cd088078e6.gif">
</p>

## System Architecture

<img src = "https://user-images.githubusercontent.com/87285536/193125830-27b49554-7abc-4943-9bd4-63962997fd41.png">

## Features

- Main Feature: 사용자가 업로드한 이미지를 AI가 분석해 닮은 동물 정보를 제공
- Additional Feature: 운세 제공 

<p align="center">
<img src = "https://user-images.githubusercontent.com/87285536/193129053-688dbd74-55ef-451f-aaea-a79a25b5ffd8.png" width="49%"> <img src = "https://user-images.githubusercontent.com/87285536/193128698-d2a4ba94-4150-4dc6-9408-57ee638c5477.png" width="49%">
</p>

**Main**|**Login**
-----|-----
<img src = "https://user-images.githubusercontent.com/87285536/193129273-d621d531-e589-4ad8-bcf3-fb73d78319f7.png" width="100%">|<img src = "https://user-images.githubusercontent.com/87285536/193129886-2d08577d-2c42-4a0a-b43a-ae26a923f39d.png" width="100%">
비회원, 회원을 선택하여 진행할 수 있습니다|회원로그인을 선택한 페이지입니다.

**Signup**|**Upload the Image**
-----|-----
<img src = "https://user-images.githubusercontent.com/87285536/193129373-a782e96b-4318-4e61-9d0d-4ff65a98a362.png" width="100%">|<img src = "https://user-images.githubusercontent.com/87285536/193130099-5ac86817-de04-4924-9df6-35b1fefd325d.png" width="100%">
회원가입 페이지 입니다.|사진을 업로드 하시면 AI가 사진을 분석합니다.

**The results of Zoodiac**|**Fortune page**
-----|-----
<img src = "https://user-images.githubusercontent.com/87285536/193130497-fca8c9da-28ef-4669-9e32-4402d8b3a853.png" width="100%">|<img src = "https://user-images.githubusercontent.com/87285536/193130779-39249a2e-bc8c-4437-ae6e-23818e41525c.png" width="100%">
AI가 분석한 상위 3개의 결과를 그림과 함께 보여줍니다.|참여한 유저들의 그림과 함께 선택했던 단어의 유사도를 기준으로 순위를 매겨 보여줍니다.

**Mypage**|**Ranking page**
-----|-----
<img src = "https://user-images.githubusercontent.com/87285536/193131987-42c1c801-efa4-4435-9138-7b68add99158.png" width="100%">|<img src = "https://user-images.githubusercontent.com/87285536/193132399-39a0d4cf-e2eb-4296-8ae9-8edfad2746eb.png" width="100%">
로그인한 계정들로 분석한 결과를 전부 확인 할 수 있습니다. |참여한 유저들의 분석 결과를 유사도를 기준으로 순위를 매겨 보여줍니다.

##  **Tech Stack**
|Dev-Ops|<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=black"> <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white"> <img src="https://img.shields.io/badge/S3%20Bucket-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white"> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon#20RDS&logoColor=black"> <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=black"> |
|----------|:-------------:|
|__Frontend__| <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=black"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=black"> <img src="https://img.shields.io/badge/styled%20components-DB7093?style=for-the-badge&logo=styled%20components&logoColor=black"> |
|__Backend__| <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"> <img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=Gunicorn&logoColor=black"> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=black"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=black"> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=black"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=black"> |
|__DB__| <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=black"> |
|__Monitoring__| <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black"> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=black"> |
|__Others__| <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=black"> <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=black"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/GitKraken-179287?style=for-the-badge&logo=GitKraken&logoColor=black"> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=black"> |

## URL

- /     　　　　　          → Startpage
- /Signinpage    → Login page
- /Signuppage  →Signuppage
- /Mainpage          → upload your image
- /Resultpage      → show your result
- /Rankpage       → show rank
- /Intropage     → tell the fortune

## Backend API
<img src = "https://user-images.githubusercontent.com/87285536/193041730-c613155c-b3d6-4283-a3ab-21890b0989a3.png" width="100%">

## AI, Dataset

- DataSet : crawling at Google with Selenium, OpenCV
- Training  [Teachable Machine with Google](https://teachablemachine.withgoogle.com/)


<img src =https://user-images.githubusercontent.com/87285536/193063153-2af2d735-9d02-44bd-9d71-d608746b91e4.gif width="100%">

## Tech Stack

|Frontend|Backend|AI|DevOps|Etc|
|:------:|:---:|:---:|:---:|:---:|
|![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)<br>![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)<br>![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?&style=for-the-badge&logo=TailwindCSS&logoColor=white)<br>![axios](https://img.shields.io/badge/axios-0.27.2-661ddf.svg?)|![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/django-092E20.svg?style=for-the-badge&logo=django&logoColor=white)<br>![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![AmazonS3](https://img.shields.io/badge/AmazonS3-569A31?style=for-the-badge&logo=AmazonS3&logoColor=white)<br>![Swagger](https://img.shields.io/badge/Swagger-85EA2D.svg?style=for-the-badge&logo=Swagger&logoColor=white)<br>![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=Gunicorn&logoColor=white)<br>![Redis](https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white)</br>|![Tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)</br>![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)<br>![Celery](https://img.shields.io/badge/Celery-37814A.svg?style=for-the-badge&logo=Celery&logoColor=white)<br>![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white)<br>![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=Opencv&logoColor=white)</br>|![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)<br>![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)<br>![Docker](https://img.shields.io/badge/docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)|![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)<br>![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)<br><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=black"><img src="https://img.shields.io/badge/GitKraken-179287?style=for-the-badge&logo=GitKraken&logoColor=white">


## **Initialization**
- clone the repository

```bash
$ git clone https://github.com/sungnam-team-b/docker.git
$ git submodule foreach git pull origin main
$ git submodule update
delete docker-compoes.yaml at backend folder
$ cd docker
```

### 1) Docker

- docker compose build and up

```bash
$ cd DoodleDoodle
$ docker-compose up --build
```

### 2) Local **execution**

```bash
$ cd DoodleDoodle/frontend
$ npm start
$ cd ../backend/backend
$  python manage.py runserver
```

## JWT

- used_library
    - `djangorestframework-jwt`
- JWT_Settings.py
    - set JWT’s default_settings
        
        <img src="https://user-images.githubusercontent.com/41159837/183143775-f17eea8b-c3d6-48cc-9ba1-c050fc3072fe.png" width="50%" height="50%"/>
        
- JWT on frontEND
    - restore tokens by using redux
    - if we need some user data, we don’t need to make connection with backend
    by opening JWT payload, we can get user data
    
- JWT on backEND
    - after we identify user by check login data, give authorization by using JWT
    - by using refresh_token, we enhanced our security level

##  Monitoring


## Prometheus

- exporter가 매트릭을 수집하고 HTTP 통신을 통해 metric data를 가져갈 수 있게 /metrics 라는 HTTP 엔드포인트를 제공한다. 그러면 Prometheus server가 이 exporter의 엔드포인트에 HTTP GET 요청을 이용하여 metric data를 pull 한다.
- 해당 노드의 metric data

<img src="https://user-images.githubusercontent.com/41159837/183143866-e2bb4650-3098-4f79-8e45-c3eb89ef032b.png" width="50%" height="50%"/>

## Grafana

- Prometheus의 시각화 도구가 부족하여 이를 직접 사용하지는 않고 대게 Grafana라는 Data Visualization tool을 이용하여 시각화하고 있다.

<img src="https://user-images.githubusercontent.com/87285536/193060775-c3105898-8663-4b1d-aca0-4b3b30c0f712.png" width="50%" height="50%"/>

Requests / Request Latency / Responses / Response Status

#**Members of Team-B**
|이름|개발분야|소개페이지|
|---|---|---|
|김준형|Front-end,AI|https://github.com/junhyeongkim2
|이정우|Back-end,DevOps|https://github.com/RayLee-Kor
|이지윤|Front-end,DevOps|https://github.com/EASYhz
|정윤호|Back-end, AI|https://github.com/yunhobb
|한지원|Back-end|https://github.com/jiwon83


