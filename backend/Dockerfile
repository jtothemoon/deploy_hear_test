# Flask 서버용 Dockerfile
FROM python:3.11

# 작업 디렉토리 설정
WORKDIR /app

# 백엔드 폴더의 모든 파일을 Docker 컨테이너로 복사
COPY . /app

# requirements.txt 파일을 설치
RUN pip install -r /app/requirements.txt

# Flask 서버 실행
CMD ["flask", "run", "--host=0.0.0.0", "--port=5000"]
