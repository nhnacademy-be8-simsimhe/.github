## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

## 심심북 스토어
>  심심한 하루, 책 한권으로 채우기!

URL : https://simsimbook.store/

개발 기간 : 2024.12.02 ~ 2025.01.24




프로젝트 소개
---
고객이 책을 검색하고 주문할 수 있는 인터넷 서점입니다.<br>
리뷰와 평점을 보고 구매할 책을 선택 할 수 있습니다..<br>
관리자는  판매할 책을 등록, 수정 할 수 있습니다. <br>
검색을 통해 원하시는 제목 또는 내용의 책을 구경할 수 있습니다.<br>
회원 또는 비회원으로 원하시는 책을 골라 장바구니에 담고 주문할 수 있습니다.<br>
회원은 포인트, 쿠폰 할인 혜택이 적용됩니다. <br>

## erd-cloud
> https://www.erdcloud.com/d/yYCTComQswgmkvBLv

## 🌱 기여자

|                         Back 제승욱                          |                         Back 김재진                          |                         Back 임채환                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| <img width="200" height="200" alt="제승욱프로필" src="https://avatars.githubusercontent.com/u/89589209?v=4"> | <img width="200" height="200" alt="김재진프로필" src="https://avatars.githubusercontent.com/u/100599484?s=96&v=4"> | <img width="200" height="200" alt="임채환프로필" src="https://avatars.githubusercontent.com/u/122259769?v=4"> |
|                     - Backend developer                      |                      -Backend developer                      |                     - Backend developer                      |
|          [🔗GitHub](https://github.com/jacobjea)           |           [🔗GitHub](https://github.com/gimzaezin)            |         [🔗GitHub](https://github.com/strongchaehwan)         |

>
>


|                         Back 김민경                          |                         Back 이주현                          |                         Back 고동원                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| <img width="200" height="200" alt="김민경프로필" src="https://avatars.githubusercontent.com/u/180384785?v=4"> | <img width="200" height="200" alt="이주현프로필" src="https://avatars.githubusercontent.com/u/80081712?v=4"> | <img width="200" height="200" alt="고동원프로필" src="https://avatars.githubusercontent.com/u/77458624?v=4"> |
|                     - Backend developer                      |                      -Backend developer                      |                     - Backend developer                      |
|          [🔗GitHub](https://github.com/gyeong22)           |           [🔗GitHub](https://github.com/jooh-yeon)            |         [🔗GitHub](https://github.com/dw9706)         |



### 개발 환경
- 개발도구: Intellij IDEA - Ultimate
- 언어: Java 21 LTS Temurin
- 빌드도구: Maven


### 개발
- Spring Framework: 6.2.0
- Spring Boot: 3.4.0
- Spring Cloud
- Spring Cloud Gateway
- Spring Cloud Netflex(Eureka)
- Spring Data JPA
- Spring Data Elasticsearch
- Spring Data Redis
- OAUTH
- JPA
  - QueryDSL
 

### 테스트
- Junit5
- Mockito
- SonarQube


### 데이터베이스
- MySQL: 8.0.37
- Redis


### 검색엔진
 - Elastic Search: 8.6.2


### ERD
- ERDCloud


### UI
- BOOTSTRAP5
- TOAST UI


### NHN Cloud
- Instance
- Secure Key Manager
- Object Storage


### 기타
- Dooray Hook Sender
- Swagger

## 프로젝트 아키텍쳐

![아키텍쳐 drawio](https://github.com/user-attachments/assets/ee7e8595-c379-4bbd-a147-ea6b8a75c3b8)

## CI/CD 무중단 배포
![simsimbook_CICD drawio](https://github.com/user-attachments/assets/cb5e23bb-89cc-4327-b5cf-60817672621b)

### ERD
![erd](https://github.com/user-attachments/assets/b329ee7c-a195-46af-b527-4a730f85220a)
---

## 프로젝트 관리

### 데일리 스크럼
![scrum](https://github.com/user-attachments/assets/f740a1e8-551c-453d-bdea-041081361603)


### WBS
![wbs](https://github.com/user-attachments/assets/cf51d863-ae60-4601-aea5-4bb84488c666)


### Kanban Borad
![board](https://github.com/user-attachments/assets/704a038c-c243-4ff3-9aeb-72800c16b0dc)





## 멤버 역할
---

### 고동원
- CI/CD
  - GitHub Action
  - Git Flow
  - 무중단 배포 서비스
  - 
- 메시지 큐 및 분산 시스템
  - RabbitMQ

- 코드 품질 및 분석
  - SonarQube

- 쿠폰
  - 쿠폰 등록 (금액 쿠폰, %쿠폰)
  - 도서 쿠폰
  - 카테고리 쿠폰
  - Welcome 쿠폰
  - 쿠폰 발급 내역
  - 사용 내역
---

### 김민경
- 검색
- 리뷰
---

### 김재진

- 주문
  - 전체적인 주문 과정, 배송, 포장 설계
  - 회원, 비회원 주문, view페이지 구현
  - 주문시 쿠폰, 포인트 포장지 적용 view페이지 구현
  - 관리자 상품의 배송상태, 주문상태 변경, 송장번호 등록 기능 구현
  - 관리자 배송비 정책 설정 기능 구현
  - 관리자 포장지 등록 기능 구현
  - 주문내역, view 페이지 구현

- 포인트
  - 보유한 포인트 구현
  - 관리자 포인트 정책 기능 구현
  - 주문, 리뷰, 포토리뷰, 회원가입시 포인트 적립 구현
  - 포인트 적립 내역, view페이지 구현
  - 주문시 포인트 사용 할인 구현
 
- 로그
  - NHN LogNCrash 사용하여 여러 서버의 로그를 하나의 콘솔에서 관리
 
- 암호화
  - NHN Cloud Secure KeyManager 사용하여 민감한 접속정보를 암호화
  
- 이미지 업로드
  - NHN Cloud Object Storage 이용 하여 이미지 등록 구현
  - 로컬 저장기능 구현
---

### 이주현
- 결제

---

### 임채환

---

### 제승욱
- 인증
  -로그인 구현
  - 소셜 로그인 구현(OAuth Payco)
  - Spring Security 적용
  - 인증 서버 구축하여 JWT 토큰 발급
  - JWT 인가 처리 구현
  - Refresh Token 재발급 구현

- 권한 및 접근 제어
  - 권한 별 접근 제한 (AOP)
  - 로그아웃 구현 (토큰 쿠키 삭제)

- 유저 관리
  - 휴면 유저 처리 구현(Spring Scheduler)
  - 휴면 유저 해제 처리 (Dooray Message API 사용)
  - 유저 탈퇴 구현
  - 회원 주소 등록 기능 (다음 API 활용)

- 기타
  - 유저 등급 변경 (순수 결제 기준)
  - Spring Cache 구현 (성능 최적화를 위한 캐시 처리)

