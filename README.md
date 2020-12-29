# SPA에서 추출한 빌드 파일 띄우는 express서버
- express-generator로 만든 프로젝트를 기반으로 설치 필요없이 쓸 수 있게 템플릿화

## PORT: 기본 3456
- 윈도우의 경우 실행스크립트 변경
  - "start": "set PORT=3456&&node ./bin/www"

## dist 파일 경로
- public: 정적리소스 파일 루트 경로(css, js, image등)
- views: html파일 경로
