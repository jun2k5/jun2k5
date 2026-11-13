<!-- 헤더 -->
<img src="https://capsule-render.vercel.app/api?type=soft&color=0:e8fafd,100:4bb8ce&height=130&section=header&text=%EB%B0%B1%EC%97%94%EB%93%9C%20%EA%B0%9C%EB%B0%9C%EC%9E%90%20%C2%B7%20%EA%B9%80%EB%B3%91%EC%A4%80&fontSize=34&fontColor=2b2b2b&fontAlignY=52&animation=fadeIn" width="100%"/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Gowun+Dodum&size=20&duration=3500&pause=1200&color=4BB8CE&center=true&vCenter=true&width=460&lines=%ED%98%B8%EA%B8%B0%EC%8B%AC%EC%9D%84+%EC%B1%84%EC%9B%8C%EB%82%98%EA%B0%80%EB%8A%94+%EA%B0%9C%EB%B0%9C%EC%9E%90;Backend+%C2%B7+Salesforce+Developer" alt="typing"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white"/>
  <a href="https://velog.io/@jun2k5"><img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=velog&logoColor=white"/></a>
  <a href="mailto:juny2k@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

<br/>

## 🧑‍💻 Experience

- 경북대학교 소프트웨어학과 (2018.03 ~ 2025.02 졸업)
- 오즈코딩스쿨 백엔드 부트캠프 16기 (2025.11 ~ 2026.05)
- 정보처리기사 (2026.06)
- KUSRC · 백엔드 개발자, Salesforce 연동 (2026.09 ~ ing)

<br/>

## 🚀 Projects

### 📝 LMS 쪽지시험 — 교육 플랫폼 시험 기능
> **오즈코딩 익스턴십** · 2026.03 · Backend · 팀장

- 쪽지시험·응시 내역 API와 데이터 모델링
- `select_related`·`prefetch_related`·`annotate`로 시험 10건 조회 쿼리 30개 → 2개
- 팀 개발 문서, 브랜치·일정 관리

**Stack** Django · DRF · PostgreSQL · Redis · Docker · AWS EC2·S3

🔗 [GitHub Repository](https://github.com/OZ-Coding-School/oz_externship_be_07) · 📖 [회고](https://velog.io/@jun2k5/ozcoding-lms-exam-feature-n-plus-1)

<br/>

### 🎮 PGTI — 유저·인증
> **부트캠프 최종 프로젝트** · 2026.04 ~ 2026.05 · Backend

- 회원가입·로그인·토큰 재발급, 카카오·네이버·구글 소셜 로그인
- Refresh Token을 HttpOnly 쿠키에 두고 회전
- 배포 환경 크로스 사이트 쿠키 문제를 SameSite=None·CORS로 해결
- 프로필 이미지 S3 Presigned URL 업로드

**Stack** Django · DRF · Simple JWT · PostgreSQL · Redis · AWS EC2·S3 · GitHub Actions

🔗 [GitHub Repository](https://github.com/Oz-union-16-Team-1/oz_union_16_BE) · 📖 [인증 설계 회고](https://velog.io/@jun2k5/ozcoding-pgti-auth-design) · 📖 [쿠키 트러블슈팅](https://velog.io/@jun2k5/ozcoding-pgti-cross-site-cookie-s3)

<br/>

### 💰 DDSY — 가계부 서비스
> **부트캠프 Django 팀 프로젝트** · 2026.02 · Backend · 팀장 (3명)

- 계좌·거래 API, 잔액 갱신을 `atomic()` + `select_for_update()`로 보호
- Celery Beat로 지출 분석 주기 작업
- Docker 개발 환경, pre-commit + Ruff

**Stack** Django · DRF · PostgreSQL · Celery · Redis · Docker

🔗 [GitHub Repository](https://github.com/OZ-BE-16-corona/corona-accountBook) · 📖 [회고](https://velog.io/@jun2k5/ozcoding-ddsy-account-book-team-lead)

<br/>

### 🌙 Danbam — 질문 일기 서비스
> **부트캠프 FastAPI 팀 미니 프로젝트** · 2026.01 · Backend

- 저장소 생성, Tortoise ORM·PostgreSQL 연결, Aerich 마이그레이션 초기 설정
- 일기 모델·서비스·API(생성·목록·조회·수정·삭제) 전체 구현
- 서버 시작 시 명언을 스크래핑해 저장하는 기능

**Stack** FastAPI · Tortoise ORM · PostgreSQL

🔗 [GitHub Repository](https://github.com/oz-main-be-16-team5/project_OZdiary) · 📖 [회고](https://velog.io/@jun2k5/ozcoding-danbam-diary-team-project)

<br/>

### 📅 meetifyr — 모임 날짜 정하기
> **부트캠프 FastAPI 과정** · 2025.12 ~ 2026.01 · Backend

- 테스트를 먼저 쓰는 TDD로 개발
- GitHub Actions CI 구성

**Stack** FastAPI · Tortoise ORM · MySQL · GitHub Actions

🔗 [GitHub Repository](https://github.com/jun2k5/OZCoding_FastAPI_meetifyr) · 📖 [회고](https://velog.io/@jun2k5/ozcoding-fastapi-meetifyr-tdd-ci)

<br/>

## ✍️ Blog

| 시리즈 | |
|---|---|
| 소프트웨어학과 4년 기록 | [보기](https://velog.io/@jun2k5/sw-major-series-intro) |
| 오즈코딩 백엔드 부트캠프 기록 | [보기](https://velog.io/@jun2k5/ozcoding-series-intro) |
| 정보처리기사 과목별 개념 정리 | [보기](https://velog.io/@jun2k5/jcg-series-intro) |
| Salesforce 입문 기록 | [보기](https://velog.io/@jun2k5/sf-series-intro) |

<br/>

## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,fastapi,postgres,mysql,redis,docker,githubactions,aws,git,linux&perline=11"/>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apex-00A1E0?style=flat-square"/>
  <img src="https://img.shields.io/badge/LWC-00A1E0?style=flat-square"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white"/>
</p>

<br/>

## 🐾 GitHub

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=jun2k5&hide_border=true" height="160"/>
</p>

<!-- 푸터 -->
<img src="https://capsule-render.vercel.app/api?type=soft&color=0:4bb8ce,100:e8fafd&height=60&section=footer" width="100%"/>
