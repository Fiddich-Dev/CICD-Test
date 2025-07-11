# 1. 자바 17 이미지 기반
FROM openjdk:17

# 2. jar 파일을 이미지 안에 복사
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} app.jar

# 3. 애플리케이션 실행 명령
ENTRYPOINT ["java", "-jar", "/app.jar"]