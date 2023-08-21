# WeHee Docs

> WeHee의 자료를 관리하는 문서 레포지토리입니다.

### Quick Links

- [Notion](https://lemonade-log.notion.site/SSAFY-PJT-f8804bbfc7b24b1e91c25a4667a75e61?pvs=4)
- [Jira](https://ssafy.atlassian.net/jira/software/c/projects/S09P12A806/boards/3230)
- [GitLab](https://project.ssafy.com/login?returnPath=%2Fsso)
- [Figma](https://www.figma.com/file/LOZntT4iuXmIPDn6SDdfK3/Main-Board?type=design&node-id=30-10&mode=design)

### How to Contribute?
[Docs 작성 규칙](operations/docs/README.md)을 참조해 WeHee의 기술 문서를 업데이트 할 수 있습니다. 

# Documentation


- [컨벤션](conventions/README.md)
  - [Git 컨벤션](conventions/git/README.md)
  - [Jira 컨벤션](conventions/jira/README.md)
    - [Jira-GitLab 연동하기](conventions/jira/jira-gitlab-integration.md)
    - [Jira 컨벤션 및 세미나](conventions/jira/jira-conventions-seminar.md)
  - [Git 및 Jira 이슈 템플릿](conventions/git/templates/README.md)
    - [버그 리포트 템플릿](conventions/git/templates/bug-report-template.md)
    - [기능 요청 템플릿](conventions/git/templates/feature-request-template.md)
    - [이슈 템플릿](conventions/git/templates/issue-template.md)
    - [PR 템플릿](conventions/git/templates/pull-request-template.md)
  - [Docs 작성 규칙](operations/docs/README.md)
- [디자인](design/README.md)
  - [로고 및 컬러 팔레트](design/logo-and-pallete.md)
  - [와이어프레임](design/wireframe.md)
  - [프로토타입](design/prototype/README.md)
      - [메인 및 회원 프로토타입](design/prototype/main-prototype.md)
      - [우리집 프로토타입](design/prototype/board-prototype.md)
      - [채팅 프로토타입](design/prototype/chatting-prototype.md)
      - [보이스룸 프로토타입](design/prototype/voice-room-prototype.md)
  - [피그마 보는 간단 가이드](design/figma-guide.md)
- [기획](proposal/README.md)
  - [프로젝트 기획서](proposal/project-proposal.pdf)
  - [요구사항](proposal/requirements/README.md)
    - [마이페이지 요구사항](proposal/requirements/mypage-requirements.md)
    - [우리집 요구사항](proposal/requirements/board-requirements.md)
    - [채팅 요구사항](proposal/requirements/chatting-requirements.md)
    - [보이스룸 요구사항](proposal/requirements/voice-room-requirements.md)
  - [자료조사](proposal/references.pdf)
- [운영](operations/README.md)

  - [기술 스택](operations/tech_stack.md)
  - [일정](operations/plan.md)
  - [역할 분담](operations/roles.md)
- [설계](architecture/README.md)
  - [architecture.drawio](architecture/architecture.drawio)
  - [전체 시스템 설계](architecture/README.md)
  - [chatting](architecture/chatting/README.md)
    - [채팅 시스템을 구현한다면, 어느 정도 수준의 설계까지 구현 가능할 것인가?](architecture/chatting/plan-for-designing-chatting-architecture.md)
    - [채팅 기능 설계 구체화](architecture/chatting/refining-chatting-feature-design.md)
    - [채팅 예시 프로젝트 실행 - Building Real-Time Apps with Spring, Cassandra, Redis, WebSocket and RabbitMQ](architecture/chatting/sample-project-jorge-acetozi.md)
    - [채팅 아키텍처 설계 - WIP](architecture/chatting/design-chatting-architecture.md)
  - [database](architecture/db/README.md)
    - [사용자 데이터베이스 테이블 설계](architecture/db/user-db-table.md)
    - [MBTI 라운지 데이터베이스 테이블 설계](architecture/db/mbti-lounge-db-table.md)
    - [사용자 및 MBTI 라운지 데이터베이스 테이블 생성&기본 데이터 삽입 SQL](architecture/db/user_lounge_init.sql)
- [development](development/README.md)
  - [How to Run](development/how-to-run.md)
  - [백엔드 개발자의 API 만들기](development/how-to-make-api-in-spring-boot.md)
  - [Spring Boot 환경 설정 - WIP](development/spring-boot-env-setting.md)
  - [도커 설정 - WIP](development/docker-setting.md)
  - [Spring WebSocket - WIP](development/spring-websocket.md)
  - [소셜 로그인을 이용한 인증 기능 구현하기 - WIP](development/authentication-development.md)
  - [채팅 기능 구현하기 - WIP](development/chatting-development.md)
  - [Annotations in Spring Boot - WIP](development/annotations-in-spring-boot.md)
  - [배포 - WIP](development/deployment.md)
- [발표](presentation/README.md)
  - [기획 발표](presentation/planning-presentation.pdf)
  - [최종 발표](presentation/final-presentation.pdf)
  - [UCC](presentation/wehee.mp4)
- [review](review/README.md)
  - [study](review/study/README.md)
    - [[책] Cracking the PM Interview: How to Land a Product Manager Job in Technology(Cracking the Interview & Career) - WIP](review/study/cracking-the-pm-interview.md)
    - [[책] 도메인 주도 설계 핵심](review/study/domain-driven-development-core.md)
    - [[책] 가상 면접 사례로 배우는 대규모 시스템 설계 기초](review/study/system-design-interview.md)
    - [[책] Building Real-Time Apps with Spring, Cassandra, Redis, WebSocket and RabbitMQ - WIP](review/study/building-real-time-apps.md)
    - [Hexagonal Architecture](review/study/hexagonal-architecture.md)
    - [OAuth를 이용한 소셜 로그인 구현](review/study/social-login-using-oauth.md)
    - [Docker](review/study/docker.md)
    - [RDBMS와 NoSQL DB의 차이](review/study/differences-between-rdmbs-and-nosql-db.md)
    - [Spring Security](review/study/spring-security.md)
    - [CSRF](review/study/csrf.md)
    - [Cassandra - WIP](review/study/cassandra.md)
    - [Redis](review/study/redis.md)
    - [Stateless와 Stateful 서비스 - WIP](review/study/stateless-and-stateful-services.md)
    - [분산 트랜잭션 - WIP](review/study/distributed-transaction.md)
  - [roadmap](review/roadmap/README.md)
    - [프론트엔드 로드맵 만들기](review/roadmap/frontend-roadmap.md)
    - [기획 로드맵 만들기 - WIP](review/roadmap/product-management-roadmap.md)
  - [story](review/story/README.md)
    - [우리의 기획이 어설플 수밖에 없는 이유](review/story/reasons-of-our-product-design-is-clumsy.md)
    - [목적이 다른 여러 사람이 각자, 그리고 공동의 목표를 이룰 방법은?](review/story/ways-of-achieving-personal-and-public-goals.md)
    - [공부하고 조사한 내용은 많은데 왜 개발은 느릴까? - WIP](review/sotry/why-development-gets-slower.md)
  - [consulting](review/consulting/README.md)
    - [week2](review/consulting/week2/README.md)
      - [week2 result](review/consulting/week2/week2-consulting-result.md)
      - [week3 plan](review/consulting/week2/week3-consulting-plan.md)
    - [week3](review/consulting/week3/README.md)
      - [week3 result](review/consulting/week3/week3-consulting-result.md)
