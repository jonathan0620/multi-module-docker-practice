# 1. JDK 기반 이미지 선택
FROM eclipse-temurin:17-jdk

# 2. JAR 파일 이름 지정
ARG JAR_FILE=build/libs/*.jar

# 3. JAR 복사
COPY ${JAR_FILE} app.jar

# 4. 앱 실행
ENTRYPOINT ["java", "-jar", "app.jar"]

