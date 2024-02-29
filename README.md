# mystery-sketch-backend

# 미스터리 스케치

유진서, 조민수, 원준석, 김영범


# Proejct - Sunshine팀 
## 소개
<p style="color: dodgerblue">캐치마인드 게임을 참고하여 만든 사이드 프로젝트입니다.</p>

백엔드 서버 코드를 저장했습니다. Frontend 소스 코드는 [여기](https://github.com/fullminji/mystery-sketch)에 있습니다.

## 저장소 구조

```
├── app.js
├── controllers
│   ├── answerController.js
│   ├── gameRoomController.js
│   ├── imageController.js
│   ├── socketController.js
│   └── userController.js
├── README.md
├── models
│   ├── answerDao.js
│   ├── gameRoomDao.js
│   ├── dataSource.js
│   ├── imgaeDao.js
│   └── userDao.js
├── package-lock.json
├── package.json
├── pull_request_template.md
├── routes
│   ├── answerRouter.js
│   ├── index.js
│   ├── gameRoomRouter.js
│   ├── imageRouter.js
│   └── userRouter.js
├── services
│   ├── answerService.js
│   ├── gameRoomService.js
│   ├── imageService.js
│   └── userService.js
└── utils
    └── error.js
```

- 백엔드 저장소 구조는 위와 같습니다.

## 기술스택
- Backend: [Express.js](https://expressjs.com)
- Frontend: [React.js](https://reactjs.org/)
  
<div align="center">
<img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
<img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
<br>
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://image.toast.com/aaaadh/alpha/2017/techblog/image%284%29.png" style="width: 100px;">

</div>

## 벤치마킹 포인트 👀

소켓 기능을 통해 실제 시간에 게임 유저들 간에 통신이 가능하므로, 실시간으로 게임 플레이어들끼리 채팅, 이동, 상태 업데이트 등의 상호작용이 가능합니다. 

### 게임 플레이 영상


https://github.com/applepc24/mystery-sketch-backend/assets/146638661/e97595d8-8c47-4515-824a-9bad5c7609e4

# Dev Story
## 기여한 사람들

| [🍑 Minsu](https://github.com/jominsu0103) | [🍇 Jinseo](https://github.com/coderjins) | [🥑 Junseok](https://github.com/applepc24) | [🥝 Youngbeom](https://github.com/pc0bum) | [🍋 Jiyeong](https://github.com/hjy961021) | [🍍 Juhee](https://github.com/Haze10425) | [🍹 Minji](https://github.com/fullminji) 
|--------------------------------------------|---------------------------------------------|-------------------------------------------|--------------------------------------------|--------------------------------------------|-----------------------------------------|--------------------------------------------

## Dev Note
[이곳](https://www.notion.so/bdb25de56d9b48cba3ddb4a2254e0180?v=24cc97035f3a43a4ab96cdd0bd483580)에 개발 과정을 팀원들이 작성하였습니다.

Backend 관련 notion은 [여기](https://www.notion.so/be7eb54fdf2f4154b88b1263cf5b8b60)에 있습니다.



