# 🚀 LuFin - 청소년 금융·경제 교육 플랫폼
<img alt="LuFin" src="/assets/luFin_landing.png">

## 📅 프로젝트 정보
- **기간**: 2025.02.24 ~ 2025.04.11 (7주)
- **참여 인원**: 6명 (FrontEnd 3/ BackEnd 3)
- **SSAFY**: 삼성 청년 SW 아카데미 12기 특화 프로젝트 **우수상** 수상

## 📝 프로젝트 개요
LuFin은 초등학교 고학년과 교사들을 위한 **금융 교육 시뮬레이션 플랫폼** 입니다.
가상화폐, 주식, 대출, 적금 등 다양한 금융 활동을 체험하며 실생활에 필요한 경제 개념을 재미있게 학습할 수 있습니다.    
청소년 금융 문맹 해소를 목표로, 신용 점수 및 자산 관리를 경험할 수 있는 환경을 제공합니다.

> **"금융의 미래를 밝히다, 루핀"**

## 🎯 목표
- **게임화된 금융 교육**: 금융 활동을 시뮬레이션하며 재미있게 학습
- **신용 시스템 도입**: 신용 점수 및 등급 관리로 금융 습관 개선
- **교사-학생 상호작용**: 교사가 경제 환경을 조성하고 학생이 참여

## ✨ 주요 기능
| 기능                  | 설명                                                                                 |
|---------------------|------------------------------------------------------------------------------------|
| 💰 가상화폐 시스템      | 미션 수행, 대출, 투자, 소비 등 다양한 활동을 통해 가상화폐 획득 및 사용                                     |
| 🏦 금융 시뮬레이션       | 주식 투자, 대출, 적금 시스템으로 실전 금융 활동을 체험                                                 |
| 🎁 아이템 상점          | 가상화폐로 구매 가능한 아이템 제공, 교내 혜택 부여                                                        |
| 📈 신용 시스템          | 신용 점수(0~100점) 및 15단계 등급 (A+ ~ F-) 관리, 신용 회생 절차 지원                                     |
| 🏫 교사-학생 상호작용    | 교사는 경제 환경을 설정하고 학생의 금융 활동을 지원, 클래스별 독립 금융 시스템 운영                      |

## 💳 신용 시스템 상세
| 신용 등급 | 점수 범위 | 대출 이자율 (단기/중기/장기) | 적금 이자율 (단기/중기/장기) |
|-----------|-----------|-----------------------------|-----------------------------|
| A+        | 95~100    | 2% / 3% / 4%                | 6% / 7% / 8%                |
| A         | 90~94     | 2% / 3% / 4%                | 6% / 7% / 8%                |
| ...       | ...       | ...                         | ...                         |
| F-        | 0~29      | 8% / 10% / 12%              | 2% / 3% / 4%                |

- **신용 점수 변동**: 적금, 대출 상환, 미션 성공 여부 등 다양한 이벤트 기반
- **회생 시스템**: F- 등급 도달 시 교사 승인 후 회생 절차 진행, F+ 등급으로 회복

## 📊 대시보드 기능
  - **🎒학생**: 자산 현황, 신용 점수 변화, 소비/투자 통계, 미션 진행 상황, 보유 아이템   
  <img alt="학생 대시보드" src="/assets/dashboard_student.png">
  
  - **🧑‍🏫교사**: 클래스별 학생 경제 활동 리포트, 신용 회생 요청 승인, 아이템 구매 승인   
  <img alt="교사 대시보드" src="/assets/dashboard_teacher_clean.png"> 
  
  
  
### 📌학생 자산 그래프
학생의 자산 구성을 시각화한 그래프입니다. 현금과 주식 자산의 비율을 한눈에 확인할 수 있어 자산 포트폴리오를 이해하기 쉽습니다.   
<img alt="학생 자산 그래프" src="/assets/dashboard_student_asset_graph.gif">
  
### 📌신용 회생 요청 (학생)
신용 등급이 F-로 하락한 학생이 교사에게 회생 요청을 진행하는 화면입니다. 교사와 상담 후 회생 절차를 시작할 수 있습니다.   
<img alt="학생 회생 신청" src="/assets/credit_recovery_student_request_clean.gif">
  
### 📌신용 회생 승인 (교사)
교사가 학생의 회생 요청을 승인하는 화면입니다. 승인이 완료되면 학생은 회생 절차를 진행할 수 있습니다.
<img alt="교사 회생 승인" src="/assets/credit_recovery_teacher_approve_clean.gif">

### 📌신용 회생 완료 (학생)
교사의 승인을 받은 학생이 회생 절차를 완료하는 화면입니다. 신용 등급이 F+로 회복되며 금융 활동이 다시 가능해집니다.   
<img alt="학생 회생 완료" src="/assets/credit_recovery_student_complete_clean.gif">

## 🏆 기대 효과
- **청소년 금융 문맹 해소**
- **금융 습관 개선 및 신용 관리 학습**
- **실생활 연계형 금융 교육**

## 🌐 서비스 구조
<img alt="서비스 구조도" src="/assets/service-architecture.png" width="700">

## 🛠️ 기술 스택

| 영역 | 기술 |
|:-----:|:-----|
| **Frontend** | ![React](https://img.shields.io/badge/React%2019-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=react&logoColor=white) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) ![JDK](https://img.shields.io/badge/JDK%2017-000000?style=for-the-badge&logo=openjdk&logoColor=white) ![JPA](https://img.shields.io/badge/JPA/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-FF6F61?style=for-the-badge&logo=claude&logoColor=white) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white) |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white) |
| **협업 도구** | ![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white) ![GitLab](https://img.shields.io/badge/GitLab-fc6d26?style=for-the-badge&logo=gitlab&logoColor=white) ![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) |

## 👥 팀원 소개

| <img alt="profile" src ="https://github.com/marunturtle.png" width ="100px"> | <img alt="profile" src ="https://github.com/seohye-ki.png" width ="100px"> | <img alt="profile" src ="https://github.com/shinyou28.png" width ="100px"> | <img alt="profile" src ="https://github.com/yes2489.png" width ="100px"> | <img alt="profile" src ="https://github.com/NekoShoot.png" width ="100px"> | <img alt="profile" src ="https://github.com/minjumost.png" width ="100px"> |
| :--------------------------------------------------------------------------: | :------------------------------------------------------------------------: | :------------------------------------------------------------------------: | :----------------------------------------------------------------------: | :------------------------------------------------------------------------: | :------------------------------------------------------------------------: |
|                                이재현 (팀장)                                 |                                   김서현                                   |                                   신유영                                   |                                  양은서                                  |                                   조홍균                                   |                                   최민주                                   |
|                [marunturtle](https://github.com/marunturtle)                 |                 [seohye-ki](https://github.com/seohye-ki)                  |                 [shinyou28](https://github.com/shinyou28)                  |                  [yes2489](https://github.com/yes2489)                   |                 [NekoShoot](https://github.com/NekoShoot)                  |                 [minjumost](https://github.com/minjumost)                  |
|                                   FE                                         |                                    BE                                      |                                     FE                                     |                                BE 팀장                                    |                                   BE / Infra                               |                                 FE 팀장                                     |

## 📝 라이선스
MIT License
