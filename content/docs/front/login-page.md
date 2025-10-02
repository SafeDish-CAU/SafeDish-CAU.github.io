---
title: Login Page
type: docs
prev: /docs/front/allergy-search
next: /docs/front/menu-page
---

## JWT/OAuth2
- Provider: Google, KaKao, Naver  
- 데모 및 시연에서는 Google 사용 예정  

## 계정 컨트롤러
##### 필수 기능
- 자동로그인, 소셜로그인, 로그아웃  

##### 예상 시나리오
- 앱 시작 -> 자동로그인 확인 -> 로그인 페이지 -> 소셜 로그인
- 앱 사용 ... -> 설정에서 로그아웃 버튼 클릭 -> 로그아웃

## 관련 API
- OAuth2 세팅은 처음 해봐서 구조 파악 다 되면 API 명세 확정 예정
- 우선 디자인 구현 후 로컬에서 테스트

## 샘플 이미지
![login page sample](/img/login-page-sample.png)