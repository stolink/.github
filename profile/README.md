# StoLink

**작가를 위한 AI 기반 스토리 관리 플랫폼**

장편 소설 집필에 필요한 복선 관리, 캐릭터 관계도, 세계관 설정, 일관성 체크를 지원하는 통합 집필 환경입니다.

---

### 웹페이지 주소
- #### https://stolink.link
- #### https://storead.stolink.link

### 개발 기간
- 2025년 12월 12일 ~ 2026년 1월 24일 (약 5주)

---

## 🎬 발표 영상 및 포스터

### 발표 영상
> 아래 이미지를 클릭하면 YouTube에서 발표 영상을 볼 수 있습니다.

[![StoLink 발표 영상](https://img.youtube.com/vi/rGBStmZVAa8/0.jpg)](https://www.youtube.com/watch?v=rGBStmZVAa8)

### 포스터
![Image](https://github.com/user-attachments/assets/3b396de4-702f-4848-ad5a-c5e217f0303a)
![Image](https://github.com/user-attachments/assets/c2007658-0c1c-4e23-8187-f99cb4f1f95f)

---

## 🛠 기술 스택 및 아키텍처

### 기술 스택

| 영역 | 기술 |
|------|------|
| **Frontend** | React 19, TypeScript, Zustand, TanStack Query, Tiptap, Tailwind CSS |
| **Backend** | Spring Boot, PostgreSQL, Neo4j |
| **AI/ML** | FastAPI, LangChain |
| **Infrastructure** | AWS, Terraform, Docker |

### 아키텍처

<img width="1280" height="720" alt="아키텍처" src="https://github.com/user-attachments/assets/513d7420-6e1d-4e31-820a-6f2839d5ac4b" />

---

## ✨ StoLink 주요 기능

### 🏠 랜딩 페이지
[랜딩 페이지](https://github.com/user-attachments/assets/1d84643e-7b0c-44c6-a074-04059a6d3cab)

### 🔐 로그인
이메일/비밀번호 및 Google OAuth 로그인을 지원합니다.
![로그인](https://github.com/user-attachments/assets/74e17a76-c0d1-47f0-9008-19212d61788a)

### 📚 서재
작품을 한눈에 관리하는 메인 대시보드. 커버 이미지, 분량, 작성 상태를 카드 형태로 확인할 수 있습니다.
![서재](https://github.com/user-attachments/assets/92f92eae-df4c-48b6-ba83-2d8bc984055b)

### ✏️ 스마트 에디터
Tiptap 기반 리치 텍스트 에디터로 몰입감 있는 글쓰기 경험을 제공합니다. 챕터/섹션 단위 디렉토리 구조, 문서 메모, 캐릭터·배경 레퍼런스를 에디터 옆에서 바로 확인할 수 있습니다.
![에디터](https://github.com/user-attachments/assets/317d9581-e801-407f-a597-be761e7daaec)

### 🔗 캐릭터 관계도
Neo4j 그래프 DB 기반 인물 관계 시각화. 동맹, 적대, 가족, 로맨스 등 관계 유형별 필터링과 캐릭터 클릭 시 상세 정보를 즉시 확인할 수 있습니다.
![관계도](https://github.com/user-attachments/assets/53b0a580-0413-468c-be89-61a2de151ee9)
![관계도 상세](https://github.com/user-attachments/assets/a1c80cea-adc8-4b58-9d51-5a3d6e24f0e1)

### 🎭 캐릭터 관리
캐릭터별 프로필, 외모, 성격, 주요 사건 기록을 체계적으로 관리합니다. AI 이미지 생성(스튜디오)으로 캐릭터 비주얼도 만들 수 있습니다.
![캐릭터 목록](https://github.com/user-attachments/assets/b47b7504-4bc5-4dec-98e6-f745c2e327b5)

**개요 · 스튜디오**
![개요 · 스튜디오](https://github.com/user-attachments/assets/4b386ca3-e443-4d6e-9f0e-af4d1b8ee601)

**성격 · 가치관**
![성격 · 가치관](https://github.com/user-attachments/assets/682e333b-2461-44e8-92ab-2bedfe142f7d)

**사건 기록**
![사건 기록](https://github.com/user-attachments/assets/e2b4bf31-d136-44bc-abe0-e434093d8e9d)

### 🧩 복선 관리
이야기 전반에 걸친 복선을 태그하고 추적합니다. 미회수/회수 완료 상태를 관리하고, 관련 캐릭터와 타임라인을 연결할 수 있습니다.

<table>
<tr>
<td><img src="https://github.com/user-attachments/assets/d159fb28-c65a-4ccb-b2a0-585717a34f36" alt="복선 현황" /></td>
<td width="280"><img src="https://github.com/user-attachments/assets/8e3694b8-a093-4be1-8d43-926336518291" width="260" alt="복선 상세" /></td>
</tr>
<tr>
<td align="center">복선 현황 대시보드</td>
<td align="center">복선 상세 (관련 캐릭터 연결)</td>
</tr>
</table>

### 🤖 AI 기능

<table>
<tr>
<td width="280" align="center"><img src="https://github.com/user-attachments/assets/f07ec282-caba-4611-ad53-1531eef6c598" width="260" alt="Check-Bot" /><br><b>Check-Bot</b><br>스토리 내용에 대해 질문하고<br>AI가 요약·분석을 제공</td>
<td width="280" align="center"><img src="https://github.com/user-attachments/assets/647dc3c8-6581-4fec-a64c-43273535c452" width="260" alt="개연성 검증" /><br><b>개연성 검증</b><br>스토리 내 모순 및 설정 오류를<br>자동 검출하고 수정 제안</td>
</tr>
</table>

### 📥 가져오기 · 내보내기
PDF, Word, 텍스트, 마크다운, EPUB, JSON 백업 등 다양한 형식으로 원고를 내보내거나 외부 문서를 가져올 수 있습니다.
![내보내기](https://github.com/user-attachments/assets/4a7ec9b1-2f65-442f-99ca-709e86ebab5a)

---

## 📖 StoRead 커뮤니티 플랫폼

StoLink에서 집필한 작품을 독자 커뮤니티에 배포하고, 독자는 작품을 열람할 수 있는 플랫폼입니다.

### 📤 커뮤니티 배포
StoLink 에디터에서 바로 StoRead로 작품을 배포할 수 있습니다. 파일 다운로드와 커뮤니티 배포 중 선택 가능합니다.
![내보내기 메뉴](https://github.com/user-attachments/assets/4fcb8994-7388-4860-99d2-b374a9ea3afa)

**Step 1.** 배포할 섹션을 선택합니다.
![Step 1 - 섹션 선택](https://github.com/user-attachments/assets/254a8dc0-da56-40b1-8c7d-3febd5bbc63d)

**Step 2.** 배포 방식(개별 배포 / 하나로 병합)을 설정합니다.
![Step 2 - 배포 설정](https://github.com/user-attachments/assets/19735cc7-252e-4de0-87cb-f5feee2c6fe0)

**Step 3.** 배포 요약을 확인합니다. 캐릭터 프로필과 인물 관계도를 함께 배포할 수 있습니다.
![Step 3 - 배포 확인](https://github.com/user-attachments/assets/0e9dcc3c-ad53-4423-aa09-c3e7a0657a51)

**배포 완료** 후 StoRead에서 작품을 확인할 수 있습니다.

### 👓 독서 뷰
독자를 위한 읽기 전용 뷰. 글자 크기 조절, 테마 변경(화이트/다크/세피아/아이보리), 관계도 보기를 지원합니다.
![독서 뷰](https://github.com/user-attachments/assets/47fc27ee-9523-404f-b1a5-4fa0ea7b4bdf)

### 📝 작품 관리
작가의 작품 관리를 지원합니다.
![작품 관리](https://github.com/user-attachments/assets/7538badd-734d-4181-8498-2eebe0fcc1cf)

### 💳 결제 구현
---

## 📁 레포지토리 안내

| 영역 | 기술 |
|------|------|
| **[stolink_frontend](https://github.com/stolink/stolink_frontend)** | 에디터 서비스 stolink의 프론트엔드 레포지토리 |
| **[stolink_spring](https://github.com/stolink/stolink_spring)** | 에디터 서비스 stolink의 백엔드 레포지토리 |
| **[stolink_fastapi_agent](https://github.com/stolink/stolink_fastapi_agent)** | 에디터 서비스 stolink의 소설 분석 레포지토리 |
| **[stolink_fastapi_image](https://github.com/stolink/stolink_fastapi_image)** | 에디터 서비스 stolink의 이미지 생성 레포지토리 |
| **[stolink-chat](https://github.com/stolink/stolink-chat)** | 에디터 서비스 stolink의 챗봇 레포지토리 |
| **[storead_frontend](https://github.com/stolink/storead_frontend)** | 독자 플랫폼 storead의 프론트엔드 레포지토리 |
| **[storead_spring](https://github.com/stolink/storead_spring)** | 독자 플랫폼 storead의 백엔드 레포지토리 |
| **[stolink_infrastructure](https://github.com/stolink/stolink_infrastructure)** | terraform 코드를 관리하는 레포지토리 |

---

## 👨‍💻 팀원 소개

| 이름 | 역할 | GitHub |
|------|------|--------|
|남현서|PM, Fullstack | https://github.com/namhyunseo |
|권동하|Fullstack | https://github.com/ssyy3034 |
|김민정|Fullstack | https://github.com/minjung0233|
|김현서|Infra, Fullstack| https://github.com/kim001hs |
|유선목|Backend, AI | https://github.com/tjsahr9191 |
