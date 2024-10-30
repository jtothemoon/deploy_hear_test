# React 앱용 Dockerfile
FROM node:20-slim

# 작업 디렉토리 설정
WORKDIR /app

# 필요한 파일 복사
COPY . /app

# 의존성 설치 및 앱 빌드
RUN npm install
RUN npm run build

# 앱 실행
CMD ["npm", "start"]
