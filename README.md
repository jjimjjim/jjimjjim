# 🌿 경지민 Portfolio

안녕하세요. 신중한 설계와 끈기로 완성해내는 풀스택 개발자 경지민입니다.
Java와 Spring 기반의 백엔드 개발을 중심으로 학습해 왔으며, React를 활용한 프론트엔드 구현과 STT·AI 요약, RAG 챗봇 연동 경험도 가지고 있습니다.
단순히 화면에 기능을 구현하는 것에서 그치지 않고, 사용자의 요청이 프론트엔드에서 백엔드, 데이터베이스, 외부 API까지 어떻게 이어지는지 고민하며 개발하고 있습니다.

---

## 🛠 Tech Stack

### 🧩 Backend
* **Language:** `Java`, `C / C++`
* **Framework & Library:** `Spring Boot`, `Spring Framework`, `JSP & Servlet`, `MyBatis`, `Node.js`
* **Database:** `Oracle SQL (JDBC / JdbcTemplate)`

### 🎨 Frontend
* `React (Vite)`, `JavaScript`, `HTML` / `CSS`, `JQuery`, `AJAX`, `Bootstrap`, `Tailwind CSS`, `Zustand`, `Axios`

### ☁️ Infra / Tools
* `GitHub`, `Notion`, `Firebase (Hosting)`, `Naver Cloud Console`

---

## 📌 Projects

### 1. 돈워리 (Don't Worry)
> **실근무 시간을 기반으로 급여를 자동 정산하고, 구인구직·커뮤니티 기능을 결합한 플랫폼**
* **개발 기간:** 2026.03 ~ 2026.04 (4인 팀 프로젝트)
* **담당 역할:** * 사용자 중심 UI/UX 설계 및 구현, 인터랙티브 웹 환경 구축
  * 회원 게시물 관리 설계 및 구현, 신고 콘텐츠 정밀 관리
* **주요 기능:**
  * 실근무 시간 기반 야간·연장·휴일 수당 자동 계산 및 월별 급여명세서 생성
  * FullCalendar API 기반 근무 일정 등록/수정 및 상세 조회 모달
  * 구인구직 플랫폼(공고 등록 · 지원 프로세스) 및 마크다운 게시판(Toast UI Editor)
* **배운 점:**
  * 근태 데이터가 급여 계산 로직과 연결되는 흐름을 이해했습니다.
  * JSP/Servlet 기반 MVC 구조에서 화면과 비즈니스 로직을 분리하는 경험을 쌓았습니다.
  * 신고·필터링 기능을 구현하며 관리자 도구 설계 시 고려할 예외 케이스를 학습했습니다.

### 2. Orbit
> **전자결재, 근태, 게시판, RAG 챗봇까지 아우르는 IT기업 시나리오 기반 그룹웨어 시스템**
* **개발 기간:** 2026.05 ~ 2026.06 (3인 팀 프로젝트)
* **담당 역할:**
  * React + Spring Boot 기반 그룹웨어 메인 페이지 전체 설계 및 구현
  * 퇴근 정정 / 연장근무 신청 기능 end-to-end 구현
  * FullCalendar 기반 개인/공용 캘린더 구현 (Zustand 상태 관리)
  * Quill 에디터 기반 사내 게시판 CRUD 및 DOMPurify를 활용한 XSS 방어
  * Oracle MyBatis 기반 비품 신청/관리 시스템 구현
  * STT + AI 요약 회의록 파이프라인 구축 및 직원 관리 권한 스코핑 설계
* **주요 기능 & 문제 해결:**
  * **📅 캘린더:** 공공데이터포털 API 429 rate-limit 문제를 Promise 레벨 캐싱 + 순차 fetch로 해결
  * **📦 비품 관리:** 탭 카운트 업데이트 race condition을 useRef 요청 ID 패턴으로 해결
  * **🎙 회의록 & AI:** Clova Speech Object Storage(STT) 및 Groq(llama-3.1-8b-instant) 활용 요약 파이프라인 구축
* **배운 점:**
  * 프론트엔드 상태관리(Zustand)와 백엔드 API가 실시간으로 동기화되는 구조를 설계하며 상태 일관성의 중요성을 배웠습니다.
  * 외부 API의 제약 조건을 캐싱 전략으로 해결하며 네트워크 자원 관리 경험을 쌓았습니다.
  * STT, LLM API 등 외부 AI 서비스를 실제 업무 도메인(회의록)에 연동하는 파이프라인 설계 경험을 얻었습니다.
  * JDK·Tomcat 버전 호환성 문제를 원인 단위로 분석해 해결하며근본적으로 접근하는 태도를 길렀습니다.

---

## 🔗 Links & Contact
* 📧 **Email:** minguri0186@gmail.com
* 🌐 **Workspace/Site:** [sukong.shop](https://sukong.shop)
