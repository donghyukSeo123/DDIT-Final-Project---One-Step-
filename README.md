# 🧑‍💼 구인구직 플랫폼 [ONESTEP]

**"구직자, 프리랜서, 기업 모두가 단 한 걸음에 필요한 정보를 얻는 플랫폼"**  
기존 구직 사이트의 한계를 보완하고, 실질적인 매칭과 편의성을 강화한 웹 기반 구인구직 서비스입니다.

본 프로젝트에서 **TA(Technical Advisor)** 및 **DA(Data Architect)** 역할을 맡아  
**DB 설계**, **외부 API 연동**, **공통 모듈화**, **기능 구현 전반**을 주도했습니다.

---

## 🔧 사용 기술

- **Language:** Java, JavaScript, SQL
- **Framework & Library:** Spring Framework, MyBatis, jQuery, Bootstrap, Apache Tiles
- **Database:** Oracle
- **API / 외부 라이브러리:**
  - 카카오 로그인 / 지도 API
  - 구글 리캡챠
  - 국세청 사업자 진위여부 API
  - 네이버 SMS API
  - Gurumi 화상회의 API
  - JavaMail (공통 메일 전송 모듈화)
  - JSOUP (뉴스 크롤링)
- **협업 툴:** GitHub, Redmine, SVN

---

## 📌 주요 담당한 기능

### [회원]
- 일반/카카오 회원가입, 로그인
- 아이디/비밀번호 찾기 (메일 전송, 비동기 처리)
- 구글 리캡챠로 봇 방지

### [구직자]
- 메인페이지 뉴스 크롤링 (JSOUP)
- 채용공고 조회 및 필터/정렬 기능 (평점순, 분야별, 지역별 등)
- 관심기업 설정 및 기업 비교 (최대 3개, 차트 시각화 포함)
- 기업 리뷰 작성 및 기업 상세 정보 열람
- 지원내역 확인 (상태 및 기업 코멘트 포함)
- 받은 제안/관심기업 관리
- 마이페이지 개인정보 수정, 비밀번호 변경

### [기업회원]
- 채용공고 등록, 지원자 열람 및 평가
- 평가완료자 관리 및 합격여부 지정
- 채용 현황 확인 (평균 평점, 합격자 필터)

### [매니저/관리자]
- 매칭 서비스 (공고 조건 기반 공개 이력서 자동 매칭)
- API 활용 화상면접 서비스 (기업별 면접방 생성, 초대 및 알림 전송)
- 관리자 기업등록 및 이미지 업로드

---

## 🧩 담당 역할 (TA, DA)

- **DB 설계 및 ERD 작성**  
  사용자, 기업, 공고, 리뷰, 지원 내역 등 주요 도메인 모델 정의

- **API 연동**  
  다양한 외부 API 통합 및 요청/응답 파싱 로직 설계

- **공통 기능 모듈화**  
  JavaMail 전송 기능을 모듈화하여 팀원들이 간편하게 사용할 수 있도록 제공

- **기능 구현 주요 파트**
  - 로그인/회원가입
  - 기업 상세/리뷰/비교
  - 구직자 마이페이지 및 지원내역
  - 기업의 지원자 관리
  - 매칭 서비스, 화상 면접 서비스

---

## 📊 특징

- 다양한 외부 API 연동을 통한 **사용자 편의성 증대**
- 기업과 구직자 양측의 정보 비교 및 분석 기능 강화
- **관심기업 기반 기업 비교 기능** (차트 시각화 포함)
- **모듈화된 메일 발송 기능**으로 유지보수성 향상
- **매칭 알고리즘 기반 자동 추천** 기능으로 관리자 효율성 확보

---

## 🏁 배운 점

- 실무와 유사한 규모의 팀 프로젝트를 통해 **요구사항 분석, DB 설계, API 연동** 등  
  다양한 영역에서의 실전 경험을 쌓음
- 비동기 처리, 데이터 흐름, 프론트-백 연동 등 **풀스택 개발자로서의 기반 강화**
- 모듈화 및 유지보수에 대한 중요성 인식
 
---

## 📬 연락

- GitHub: [https://github.com/donghyukSeo123](https://github.com/donghyukSeo123)
- Email: ehdgur534@naver.com

---

> **기술과 사람을 잇는 플랫폼, ONESTEP**  
> 사용자 경험과 기능의 깊이를 함께 고민하며 만든 실전형 구인구직 웹사이트입니다.
