## Node.js + npm 세팅
## Node.js + Webpack 환경 프로젝트 구조

my-cesium-project/

├── index.html # 브라우저에 보여줄 기본 HTML 문서

├── main.js (또는 index.js) # 지도 초기화 및 Cesium 관련 코드

├── package.json # 프로젝트 설정 (npm 의존성, 실행 스크립트 등)

├── /node_modules/ # npm install로 설치된 라이브러리 모음

│

├── /css/

│ └── main.css # 사용자 정의 스타일

├── /js/

│ └── CesiumConfig.js # Cesium Ion access token 같은 설정

│

└── /public/ (선택적) # 이미지, 아이콘 같은 정적 파일

