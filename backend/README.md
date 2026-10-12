# Backend

Java / Spring Boot 서비스 백엔드 자리입니다. 빌드 설정과 실행 코드는 아직 없습니다.

패키지는 `src/main/java/com/pawdiary/`를 기준으로 준비했습니다. Java 버전과 Maven/Gradle을 선택한 뒤 실제 프로젝트를 생성하세요.

```text
com/pawdiary/
  global/config/
  global/error/
  domain/pet/
  domain/record/
  domain/diary/
  integration/ai/
```

`src/main/resources/`는 설정 파일, `src/test/java/com/pawdiary/`는 필요한 테스트 자리입니다.

첫 구현: AI API 클라이언트, 사진 기록 저장, 일기 생성·조회. 각 도메인 세부 클래스는 필요한 시점에 추가합니다. 실행 명령은 빌드 도구를 정한 뒤 문서화합니다.
