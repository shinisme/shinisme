<!-- =========================
        HEADER
========================= -->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:C2D3FF,100:E9D4FF&height=230&section=header&text=Shin%20Seungyeon&fontSize=52&fontColor=3B3F73&animation=fadeIn&fontAlignY=38&desc=Android%20%C2%B7%20Web%20%C2%B7%20Spring%20Boot&descAlignY=58&descSize=18"
    width="100%"
  />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=900&color=6B7BEA&center=true&vCenter=true&width=700&lines=Android+with+Kotlin+%C2%B7+Jetpack+Compose;Web+with+React+%C2%B7+Spring+Boot;Connecting+Screens+to+Real+APIs"
      alt="Typing SVG"
    />
  </a>
</p>

<p align="center">
  React로 웹 프론트엔드를 시작해 Spring Boot로 서버를, Kotlin · Jetpack Compose로 Android를 개발하고 있습니다.<br/>
  API 명세와 실제 응답을 꼼꼼히 맞춰 보고, 코드 리뷰로 팀과 기준을 맞추는 과정을 좋아합니다.
</p>

<p align="center">
  <a href="mailto:syshin0608@gmail.com"><img src="https://img.shields.io/badge/Email-syshin0608%40gmail.com-8FA8FF?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/39-play-sopt-android/seungyeon-shin"><img src="https://img.shields.io/badge/PLAY_SOPT_39th-Android-3DDC84?style=flat-square&logo=android&logoColor=white"/></a>
  <a href="https://github.com/DGU-UMC-11th/PE-Web-B"><img src="https://img.shields.io/badge/UMC_DGU_11th-Web_/_Spring-C2B5FF?style=flat-square&logo=springboot&logoColor=white"/></a>
</p>

<br/>

---

## 🚀 주요 프로젝트

### 🍽️ [캐치테이블 리디자인 — '함께 고르기' 투표](https://github.com/SOPT-all/39-COLLABORATION-ANDROID-CATCHTABLE)

**SOPT 39기 합동세미나 · Android · 홈 화면과 진행 중인 투표 조회 담당**

`Kotlin` `Jetpack Compose` `Retrofit` `Hilt` `Coil`

친구와 함께 식당을 고르는 투표 기능을 더한 예약 앱 리디자인 프로젝트입니다.

* 하단 내비 · 탭바 **공통 컴포넌트** 구현
* 홈 화면을 **Route / Screen / ViewModel**로 분리하고 네비게이션에 연결
* 진행 중인 투표 조회 API를 **Dto → Mapper → Repository → UseCase → ViewModel**로 계층을 나눠 연동
* 화면 복귀 시(`ON_RESUME`) 다시 조회해 투표 상태가 **항상 최신으로 보이도록** 처리

---

### 🎬 [UMCine — 영화 평점 서비스](https://github.com/DGU-UMC-11th/PE-Web-B)

**UMC 11기 · Web / Spring · 백엔드 API와 React 화면 연결**

`Java 21` `Spring Boot` `JPA` `MySQL` `H2` `React` `TypeScript`

회원가입 · 로그인 후 영화에 평점을 남기는 서비스로, 서버 API부터 화면 연결까지 직접 맡았습니다.

* 평점 **CRUD REST API**와 Bean Validation · 전역 예외 처리 구현
* **JWT 로그인 + AuthInterceptor**로 인증, 다른 사람의 평점 수정은 **403**으로 막는 인가 처리
* **H2 통합 테스트 7개**와 Postman으로 검증
* 완성한 API를 **React 화면과 직접 연결**

---

### 📸 [PICDAY — 사진관 예약 서비스](https://github.com/UMC-PICDAY/PICDAY_FE)

**UMC 10기 데모데이 · Frontend · 마이페이지 담당**

`React` `TypeScript` `Vite` `Tailwind CSS` `Zustand` `TanStack Query`

조건에 맞는 사진관을 찾고 예약 · 리뷰를 관리하는 서비스입니다.

* 마이페이지 **예약 상세 · 취소 · 재예약** 흐름 구현
* **0.5점 단위** 리뷰 작성 기능 구현
* 프로필 수정 · 닉네임 중복 확인 구현
* 반복되는 UI를 **공통 컴포넌트**로 분리

---

### 🎈 [놀잇 — 세대를 잇는 놀이 문화 앱](https://github.com/SOPT-all/39-SOPKATHON-ANDROID-ANDROID1)

**SOPT 39기 솝커톤 (1박 2일) · Android · 디자인 시스템과 마이페이지 담당**

`Kotlin` `Jetpack Compose` `Retrofit` `Hilt`

중고등학생이 소개한 요즘 유행을 50~64세가 직접 따라 해보고 인증하는 문화 미션 앱입니다.

* CompositionLocal 기반 **디자인 시스템**(Color · Typography 11종)과 공통 컴포넌트 구성
* 마이페이지 **Loading · Success · Error** 상태 흐름 구현
* 실패 응답의 **에러 code별로 안내 문구를 분리**

---

### 📱 모바일소프트웨어 Android 앱

**전공 수업 · Android · 개인 과제**

`Kotlin` `Jetpack Compose` `Coroutine` `Retrofit` `Coil` `ViewModel` `StateFlow`

* **사진 그리드 앱**: 코루틴 · Retrofit · Coil로 서버 사진을 그리드로 표시, **단위 테스트 6개**
* **적응형 할 일 앱**: 600 / 840dp 기준 **1-pane ↔ 2-pane** 전환, **단위 테스트 14개 · UI 테스트 4개**

<br/>

---

## 💼 활동 경력

<table>
  <thead>
    <tr>
      <th>활동</th>
      <th>역할</th>
      <th>기간</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/39-play-sopt-android">PLAY SOPT 39기</a></td>
      <td>Android</td>
      <td>2026.10 ~ 현재</td>
    </tr>
    <tr>
      <td><a href="https://github.com/DGU-UMC-11th">UMC 동국대 11기</a></td>
      <td>운영진 · Web / Spring</td>
      <td>2026.09 ~ 현재</td>
    </tr>
    <tr>
      <td>UMC 10기</td>
      <td>Web 파트 수료</td>
      <td>2026.03 ~ 2026.08</td>
    </tr>
    <tr>
      <td>정보통신공학과 학생회</td>
      <td>홍보부국장</td>
      <td>2026.02 ~ 현재</td>
    </tr>
    <tr>
      <td>Farm System 3기</td>
      <td>IoT 트랙</td>
      <td>2024.05 ~ 2024.12</td>
    </tr>
  </tbody>
</table>

<br/>

---

## 🛠 기술 스택

### Android
<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white"/>
  <img src="https://img.shields.io/badge/Retrofit-3E4348?style=flat-square&logo=square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hilt-1F7A4D?style=flat-square&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Coroutine-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/>
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/Java-E76F00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white"/>
</p>

### Frontend
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zustand-8A5A2B?style=flat-square"/>
</p>

### Tools
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white"/>
</p>

<br/>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E9D4FF,100:C2D3FF&height=120&section=footer" width="100%"/>
</p>
