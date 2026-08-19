<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:E0234E&height=160&section=header&text=Backend%20Engineer&fontColor=ffffff&fontSize=42&fontAlignY=35&desc=NestJS%20·%20TypeScript%20·%20PostgreSQL&descAlignY=55&descSize=16" width="100%" />

<div align="center">

**틀리면 바로 티가 나는 서비스**의 서버를 만듭니다 — 통화가 안 붙거나, 결제가 막히거나, 알림이 안 가거나.

</div>

<br/>

|  |  |
|---|---|
| **도메인** | 상담 시스템 (보험·카드) → 매장 결제 (POS) → 학교·학부모 서비스 |
| **규모** | 월 사용자 **90만** |
| **지금** | 구·신 서버 병행 이관 · 크롤링 파이프라인 안정화 · 저장소 3곳에 걸친 릴리스 경계 설계 |

<br/>

## 🔧 실무에서 푼 문제

- **크롤링 진단 화면** — 실패를 학교별·원인별로 집계. *코드가 아니라 상대 쪽 방화벽이 우리 IP를 막은 것*을 여기서 규명
- **부분 실패 격리** — 한 곳의 오류가 회차 전체를 무효로 만들던 구조 개선
- **무중단 세대 교체** — 구버전·신버전 동시 운영하며 기능 이관
- **만료 자동 감시** — 1년 주기 인증서 갱신을 사람 기억에서 분리

## 🤖 직접 만든 것

**[이대리 · personal_agents](https://github.com/JSL107/personal_agents)** — Slack 멀티 에이전트 업무 자동화 봇
PR 리뷰 · 하루 회고 · 코드 작성을 역할별로 나눠 맡깁니다. 만들다 보니 서버와 같은 문제가 나왔습니다 — 승인 없이 외부에 쓰는 걸 어떻게 막지, 조용히 실패하면 어떻게 알아채지, 같은 작업이 두 번 돌면 어떻게 되지.

<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
<img src="https://img.shields.io/badge/BullMQ-DD2C00?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Slack_Bolt-4A154B?style=flat-square&logo=slack&logoColor=white" />

## ⚙️ Stack

|  |  |
|---|---|
| **서버** | <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white" /> <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" /> |
| **데이터** | <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" /> |
| **인프라** | <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" /> <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" /> |

## 📈 Activity

<img src="https://github-readme-activity-graph.vercel.app/graph?username=JSL107&theme=react-dark&hide_border=true&area=true&custom_title=Contribution%20Graph" width="100%" />

<img src="https://streak-stats.demolab.com/?user=JSL107&theme=dark&hide_border=true&date_format=Y.%20n.%20j" />

<br/>

<a href="https://jsl107.github.io"><img src="https://img.shields.io/badge/Blog-jsl107.github.io-000000?style=for-the-badge&logo=astro&logoColor=white"/></a>
<a href="mailto:juneseok81@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
