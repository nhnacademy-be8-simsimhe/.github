## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

## 심심이의 서재
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
 - 쿠폰
 - 무중단
---

### 김민경
- 검색
- 리뷰
---

### 김재진

- 주문
  - 전체적인 주문 과정 설계
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
  - NHN Cloud Scure KeyManager 사용하여 민감한 접속정보를 암호화
  
- 이미지 업로드
  - NHN Cloud Object Storage 이용 하여 이미지 등록 구현
  - 로컬 저장기능 구현
---

### 이주현
- 결제

---

### 임채환
- 책
- 장바구니
---

### 제승욱
- 인증
- OAuth
- 회원 
