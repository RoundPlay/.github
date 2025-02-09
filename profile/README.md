# 공연 정보 지도 서비스 (Performance Map)

🎶 공연 정보를 한눈에! 지도에서 쉽게 찾아볼 수 있는 웹 서비스 🎶

이 프로젝트는 공연 정보를 지도에서 쉽게 검색하고 확인할 수 있도록 구성된 웹 애플리케이션입니다.  
사용자는 지도에서 핀을 클릭하여 공연 정보를 확인할 수 있으며, 공연 정보 등록 및 리뷰 작성 등의 기능도 지원합니다.

## 🚀 프로젝트 개요

### 📌 목표

✅ 공연 정보를 지도에서 한눈에 조회  
✅ 사용자가 공연을 등록하고 관리 가능  
✅ 프론트엔드와 백엔드 API를 연계하여 데이터 제공  

## 🛠️ 기술 스택

**Frontend:** React, TypeScript, Axios, Tailwind CSS, React Router, React Query  
**Backend:** Node.js, Express, MongoDB, Mongoose, JWT (로그인)  
**Database:** MongoDB Atlas  
**Cloud & Deployment:** GitHub Actions, Render 

## 📌 프로젝트 진행 방식

### 🗺️ 빠른 개발을 위한 프로세스

1️⃣ 아이디어 구상 (완료)  
2️⃣ 프론트엔드가 UI를 빠르게 구현  
3️⃣ 프론트엔드에서 UI 기반으로 API 명세서 작성  
4️⃣ 백엔드가 API 명세서 기반으로 개발 진행  
5️⃣ 프론트엔드 & 백엔드 연결 및 최적화  

💡 일반적인 개발 프로세스에서는 피그마(Figma)로 프레임을 만들고 API 명세서를 함께 작성한 후 개발을 진행하지만, 해커톤 특성상 UI를 먼저 개발하면서 API 명세서를 동시에 만들고 작업을 빠르게 진행합니다.

## 🎨 프론트엔드 개발

### 📌 주요 기능

✅ 공연 정보를 지도에 핀으로 표시  
✅ 공연 상세 페이지에서 정보 확인  
✅ 공연 등록 기능  
✅ 공연 좋아요 확인


### 📌 UI 디자인

![Image](https://github.com/user-attachments/assets/29dd7347-7004-47d6-9aee-17253906d008)
![Image](https://github.com/user-attachments/assets/b144c7fe-90f1-4e0c-9ca8-08b402c78793)
![Image](https://github.com/user-attachments/assets/de085db9-9dbe-4938-b707-27f5e75ba6c4)
## 💾 백엔드 개발

### 📌 주요 기능

✅ 공연 데이터 CRUD (Create, Read, Update, Delete)  
✅ MongoDB에서 공연 데이터 조회  
✅ 사용자 로그인 & 인증 (JWT 기반)  
✅ 공연별 리뷰 작성 기능 추가 예정  

### 📌 API 명세서

API 명세서는 프론트엔드 개발 진행과 동시에 작성됩니다.  

## 📂 폴더 구조

```plaintext
performance-map
├── frontend/         # 프론트엔드 (React)
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── README.md
│   └── ...
│
├── backend/          # 백엔드 (Node.js + Express)
│   ├── models/       # MongoDB 모델
│   ├── routes/       # API 라우트
│   ├── controllers/  # 비즈니스 로직
│   ├── config/       # 환경 변수 설정
│   ├── server.js
│   ├── package.json
│   ├── README.md
│   └── ...
│
└── README.md         # 프로젝트 설명
