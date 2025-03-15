# MemeSphere (Forked)

이 프로젝트는 **밈코인 정보를 한 곳에서 확인하고, 가격 알림을 설정**할 수 있는 웹 애플리케이션입니다.

> **📢 본 레포지토리는 원본 팀 프로젝트에서 포크하였습니다.**  
> 원본 프로젝트는 [MemeSphere 팀 레포지토리](https://github.com/TeamMemeSphere/Frontend-MemeSphere)에서 확인할 수 있습니다.(현재 비공개)

<br/>

## 🎯 프로젝트 개요
- **개발 기간:** 2025년 1월 ~ 2025년 2월 (8주)
- **사용 기술:** React, TypeScript, Vite, Spring Boot
- **주요 기능:**
  - 밈코인 시세 조회 (실시간 데이터 연동)
  - 관심있는 코인 사용자화
  - 관심 코인 가격 알림 설정
  - 사용자 커뮤니티 (실시간 채팅)
  - 밈코인 가격 맞추기 게임
  

<br/>

## 🛠️ 구현 담당 부분

### ✅ **커뮤니티 페이지:**
- 현재 시장의 공포탐욕지수 제공
- 사이트에 등록된 밈코인의 심볼과 최신 채팅 데이터 미리보기

### ✅ **알림 기능:**
- 원하는 코인에 대해 기준 시간당 변동성 설정 가능
- 사용자가 지정한 가격 변동성 발생시 서버로부터 데이터 수신(SSE)
- 알림 히스토리로 현재까지의 내역 확인 가능

<br/>

## 📸  스크린샷
### 알림 설정 컴포넌트
<img width="573" alt="Image" src="https://github.com/user-attachments/assets/39e1e4a9-5b47-47f0-b850-83f87177284f" />
좌측 상단 등록하기에서 코인 이름, 변동성, 기준 시간, 상승/하락을 선택하여 등록할 수 있습니다.

사이트 내에 존재하는 코인들을 드롭박스화 하여 사용자 입력에 따라 선택할 수 있고, 코인 이름과 심볼 중 하나만 선택하면 나머지가 자동완성 됩니다.


<img width="1467" alt="Image" src="https://github.com/user-attachments/assets/73d2582a-0826-4fea-b3c5-cdd3d9fdb3a7" />


시연 영상


https://github.com/user-attachments/assets/3d0b369a-2e18-4438-9789-342b939bfdac

### 커뮤니티 페이지
공포탐욕지수, 뉴스, 코인 카드로 구성됩니다.


<img width="1032" alt="Image" src="https://github.com/user-attachments/assets/0fee9dc7-17b2-41fa-b31a-98606a495082" />