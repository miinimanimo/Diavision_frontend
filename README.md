# Diavision Frontend

Diavision은 안과 진단을 위한 AI 기반 웹 애플리케이션입니다.

## 프로젝트 개요

이 프로젝트는 React와 TypeScript를 사용하여 구축된 프론트엔드 애플리케이션입니다. 

## 주요 기능

- 👁️ 안저 이미지 업로드 및 분석
- 🤖 AI 기반 진단 결과 제공
- 📊 환자 정보 관리
- 📱 반응형 웹 디자인

## 기술 스택

- **Frontend**: React 19, TypeScript
- **Styling**: CSS, Styled Components


## 설치 및 실행

### 필수 요구사항
- Node.js (v16 이상)
- npm 또는 yarn

### 설치 방법

1. 레포지토리 클론
```bash
git clone https://github.com/miinimanimo/Diavision_frontend.git
cd Diavision_frontend
```

2. 의존성 설치
```bash
npm install
```

3. 개발 서버 실행
```bash
npm start
```

브라우저에서 [http://localhost:3000](http://localhost:3000)으로 접속하여 애플리케이션을 확인할 수 있습니다.

## 사용 가능한 스크립트

### `npm start`
개발 모드로 애플리케이션을 실행합니다.

### `npm test`
테스트 러너를 대화형 감시 모드로 실행합니다.

### `npm run build`
프로덕션용 빌드를 `build` 폴더에 생성합니다.

### `npm run deploy`
GitHub Pages에 애플리케이션을 배포합니다.

## 프로젝트 구조

```
src/
├── components/          # 재사용 가능한 컴포넌트
│   ├── icons/          # 아이콘 컴포넌트
│   └── Navbar/         # 네비게이션 바
├── pages/              # 페이지 컴포넌트
│   ├── Analysis/       # 이미지 분석 페이지
│   ├── Home/           # 홈 페이지
│   ├── Login/          # 로그인 페이지
│   ├── MyPage/         # 마이페이지
│   └── PatientRegistration/ # 환자 등록 페이지
├── App.tsx             # 메인 앱 컴포넌트
└── firebase.ts         # Firebase 설정
```

## 배포

이 프로젝트는 GitHub Pages를 통해 임시 배포됩니다. 배포된 사이트는 [https://miinimanimo.github.io/Diavision_frontend](https://miinimanimo.github.io/Diavision_frontend)에서 확인할 수 있습니다.



## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.
