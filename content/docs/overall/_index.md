---
title: Overall
type: docs
weight: 1
prev: /
next: docs/front/
---

![Overall structure](/img/overall-structure.png)

## 어플
##### React Native
- 소규모 프로젝트에서 하나의 코드베이스로 IOS/Android 동시 개발은 큰 장점
- 카메라 및 위치 기반 서비스가 필요한데, 검증된 라이브러리 존재
## 메인서버
##### Spring Boot
- JWT/OAuth2 사용이 쉽고 JPA로 인해 DB 관련 개발이 빠르게 가능함
- 추후 기능이 늘어나거나 규모가 확장되는 상황에 대응 가능
##### MySQL
- RDB 중 사용해본 경험이 있고 현재 프로젝트에 적용했을 때 큰 결함은 없음
## 추천서버
##### FastAPI
- 메뉴명에 따라 예상되는 기본 재료를 추천하는 기능에만 사용될 예정이기에 간결하고 빠른 코딩이 가능해 선택
##### Neo4j
- 추천 시스템에 관계형DB보다 그래프DB가 필요해 채택
- 적지 않은 용량의 클라우드DB를 제공 