# 1. Base Image 설정
FROM openjdk:11-jdk-slim

# 2. 작업 디렉토리 설정
WORKDIR /app

# 3. JAR 파일 복사
COPY target/Kkabi_Backend-0.0.1-SNAPSHOT.jar app.jar

# 4. 실행 명령어 설정
ENTRYPOINT ["java", "-jar", "app.jar"]
