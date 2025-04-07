# todo-app-springboot
스프링부트 기반 할 일 관리 백엔드 서비스

* 주요 기능
  1. 회원가입 / 로그인 (JWT 인증)
  2. 할 일 등록 / 조회 / 수정 / 삭제
  3. 할 일 완료 여부, 기한 설정
  4. 사용자별 할 일만 접근 가능

* 기술 스택
  - 언어 : Java 17
  - 프레임워크 : Spring Boot 3.x
  - 빌드 도구	: Gradle or Maven
  - 데이터베이스 :	MySQL (개발 단계에서는 H2 가능)
  - ORM	: Spring Data JPA
  - 인증 방식	: JWT + Spring Security
  - API 문서화 (선택) :	Swagger (springdoc-openapi)
