# 📁 SmarTree 기본 제공 폴더 템플릿

## 1. 개발자 / 엔지니어용 (Software & Tech)
> Project/Source/Build/Doc의 엄격한 분리, 임시/캐시 파일 정리, 버전 관리와 연결되는 구조
- 파일 특징: 소스 코드, 빌드 산출물, SDK, 환경설정, DB 덤프, 문서 파일

### Light
```text
Desktop/
└── Dev_Workspace/
    ├── Projects/          # 소스 코드 및 레포지토리 모음
    ├── Sandbox/           # 간단한 코드 테스트 및 알고리즘 풀이
    ├── Resources/         # 폰트, 아이콘, 수동 라이브러리, 테스트 DB
    └── Docs/              # 메모, 기술 문서, 이력서
```

### Standard
```text
Desktop/
└── Developer_Space/
    ├── 01_Projects/       # 소스 코드 및 레포지토리
    │   ├── Active/        # 현재 개발/유지보수 중인 프로젝트
    │   ├── Sandbox/       # 테스트, PoC, 연습용 코드
    │   └── Archive/       # 완료된 프로젝트 보관소
    │
    ├── 02_Resources/      # 프로젝트 공통 자원
    │   ├── Assets/        # 아이콘, 소스 그래픽, 사운드
    │   ├── Libraries/     # 로컬 .dll, 수동 외부 패키지
    │   ├── Databases/     # 로컬 DB 덤프 (.sql), 테스트용 DB
    │   └── Tools/         # 무설치 유틸리티, 스크립트 (.ps1, .bat)
    │
    ├── 03_Documents/      # 기술 문서 및 기록
    │   ├── Notes/         # 개발 일지, 스터디 노트, Cheatsheet
    │   ├── Specifications/# 기획서, API 명세서, 아키텍처 설계도
    │   ├── References/    # 참고 자료, 논문, PDF
    │   └── Career/        # 이력서, 포트폴리오, 자격증
    │
    └── 04_Outputs/        # 프로젝트 외부 추출 결과물
        ├── Builds/        # 테스트용 실행 파일 (.exe, .zip)
        ├── Releases/      # 정식 배포 버전 모음
        └── Packages/      # 패키지 파일 (.nupkg 등)
```

### Professional
```text
Desktop/
└── Dev_Environment/
    ├── 01_Repositories/   # 소스 코드 저장소 (소속/성격별)
    │   ├── Company/       # 회사 / 외주 / 팀 프로젝트
    │   ├── Personal/      # 개인 사이드 프로젝트
    │   ├── OpenSource/    # 오픈소스 기여 및 클론 레포
    │   └── Labs/          # PoC, R&D, 알고리즘 풀이
    │
    ├── 02_Resources/      # 자원 및 환경 설정
    │   ├── Assets/        # 공통 그래픽, 아이콘, 폰트
    │   ├── Libraries/     # 외부 라이브러리, 모듈
    │   ├── Databases/     # DB 마이그레이션 스크립트, DB 덤프
    │   └── Tools/         # 커스텀 CLI, 무설치 유틸리티, 스크립트
    │
    ├── 03_Knowledge/      # 지식 및 문서 자산
    │   ├── Architecture/  # 시스템 아키텍처, ERD, 시퀀스 다이어그램
    │   ├── Specifications/# API Specs, 기획서
    │   ├── References/    # E-books, 기술 논문, 스펙 문서
    │   └── Career/        # 이력서, 포트폴리오
    │
    └── 04_Outputs/        # 배포 및 아티팩트
        ├── Builds/        # 로컬 빌드 바이너리
        ├── Releases/      # 정식 배포 릴리스
        └── Packages/      # NuGet, npm 등 직접 빌드한 패키지
```

## 2. 크리에이터 / 디자이너용 (Media & Design)
> 원본과 편집본/추출본의 확실한 분리, 용량이 큰 임시/렌더링 파일 감지, 에셋 재활용 보관함 구조
- 파일 특징: 대용량 원본(RAW, Footage), 에셋(폰트, 3D, 텍스처, BGM), 프로젝트 파일(PSD, AI, prproj), 결과물(MP4, PNG)

### Light
```text
Desktop/
└── Media_Workspace/
    ├── Works/             # 작업 중인 프로젝트 파일 (.psd, .ai, .prproj)
    ├── Sources/           # 이미지, 영상 소스, 폰트, BGM
    └── Exports/           # 최종 추출된 이미지/영상 결과물
```

### Standard
```text
Desktop/
└── Creative_Space/
    ├── 01_Works/          # 현재 진행 중인 작업 (Project Files)
    │   ├── Active/        # 작업 진행 중인 프로젝트 (.psd, .ai, .prproj, .aep)
    │   └── Archive/       # 완결된 프로젝트 (프로젝트 파일만 압축/보관)
    │
    ├── 02_Footage_Sources/# 원본 소스 및 미디어 파일
    │   ├── Raw_Media/     # 촬영화질 원본, RAW 사진, 녹음 파일 (순수 원본)
    │   └── Stock_Scraps/  # 외부 수집 무료/유료 스톡 영상, 컷 소스
    │
    ├── 03_Assets/         # 재사용 가능한 에셋 보관소
    │   ├── Fonts/         # 폰트 파일 (.ttf, .otf)
    │   ├── Audio/         # BGM, 효과음 (SFX)
    │   ├── Graphics/      # LUT, 3D 모델, 텍스처, 자막 템플릿/효과
    │   └── References/    # 레퍼런스 이미지, 무드보드 스크랩
    │
    └── 04_Exports/        # 결과물 및 출력 파일
        ├── Renders/       # 시안, 가렌더링 검토용 (SmarTree 주기적 용량 정리 제안 대상)
        └── Final/         # 최종 완성작 (MP4, High-Res PNG, PDF)
```

### Professional
```text
Desktop/
└── Studio_Environment/
    ├── 01_Projects/       # 클라이언트 / 채널별 작업 프로젝트
    │   ├── Clients/       # 외주 및 기업 클라이언트 프로젝트
    │   ├── Personal/      # 자체 유튜브, 개인 아트워크 작업
    │   └── Archive/       # 완결 프로젝트 패키지
    │
    ├── 02_Footage_Sources/# 대용량 미디어 소스 (날짜/촬영별)
    │   ├── Video_Raw/     # 영상 원본 Footage (4K, LOG 프로필 등)
    │   ├── Audio_Raw/     # 동시녹음, 보이스오버 원본
    │   └── Photo_Raw/     # 카메라 RAW 이미지 파일
    │
    ├── 03_Library_Assets/ # 스튜디오 공통 에셋 라이브러리
    │   ├── Fonts/         # 상업용 폰트 라이선스 모음
    │   ├── Audio/         # 정식 라이선스 BGM, SFX
    │   ├── Presets_LUTs/  # 색보정 LUT, 에프터이펙트 프리셋, 자막 바
    │   ├── 3D_Textures/   # 3D 모델링, 텍스처, HDRI
    │   └── References/    # 무드보드, 벤치마킹 자료
    │
    └── 04_Deliverables/   # 검수 및 최종 제출용
        ├── Proofs/        # 클라이언트 검수용 피드백 파일 (Draft)
        ├── Masters/       # 최종 납품 마스터 파일 (무손실, 고화질)
        └── Promos/        # 홍보용 숏폼, 썸네일, 포스터
```

## 3. 직장인 / 사무직용 (Office & Business)
> 연도별/분기별/프로젝트별 정돈, 다운로드 폴더에 쌓이는 일회성 문서 정리, 서식(템플릿) 관리하는 구조
- 파일 특징: 문서 파일(Excel, Word, PPT, PDF), 계약서, 영수증, 회의록, 이메일 첨부파일

### Light
```text
Desktop/
└── Office_Workspace/
    ├── Documents/         # 보고서, 기획서, 일반 업무 문서
    ├── Business/          # 계약서, 공문, 지출 결의서/영수증
    ├── Projects/          # 진행 중인 과제/프로젝트
    └── Archive/           # 완료된 업무 및 지난 자료 보관
```

### Standard
```text
Desktop/
└── Work_Space/
    ├── 01_Projects/       # 담당 프로젝트 & 주요 과제
    │   ├── Active/        # 현재 진행 중인 프로젝트/업무
    │   └── Archive/       # 종료된 프로젝트 (연도별 보관)
    │
    ├── 02_Business_Docs/  # 행정 & 계약 & 결의 서류 (중요 문서)
    │   ├── Contracts/     # 계약서, NDA, 협약서
    │   ├── Official/      # 수발신 공문, 협조문
    │   └── Finance/       # 지출결의서, 영수증, 견적서, 세금계산서
    │
    ├── 03_Resources/      # 업무 지원 자원 & 서식
    │   ├── Templates/     # 회사 공통 보고서 양식, PPT 템플릿, 로고
    │   ├── Manuals/       # 업무 매뉴얼, 사규, 시스템 사용 가이드
    │   └── References/    # 시장 조사 자료, 경쟁사 분석, 통계 데이터
    │
    └── 04_Meetings_Reports/# 회의 & 정기 보고
        ├── Weekly_Monthly/# 주간/월간 업무 보고서
        └── Meeting_Notes/ # 회의록, 미팅 메모
```

### Professional
```text
Desktop/
└── Management_Space/
    ├── 01_Operations/     # 팀/부서 운영 & 관리
    │   ├── Team_Manage/   # 조직도, R&R, 업무 분장
    │   ├── HR_Personnel/  # 근태, 채용, 평가, 교육 자료
    │   └── Budget_KPI/    # 부서 예산, KPI 목표 및 실적 관리
    │
    ├── 02_Projects_PMO/   # 프로젝트 관리 (PMO)
    │   ├── Current/       # 진행 중인 전체 프로젝트 모니터링
    │   ├── External/      # 고객사/외주업체 협업 프로젝트
    │   └── Past_Projects/ # 완료 과제 아카이브
    │
    ├── 03_Legal_Finance/  # 법무 & 재무 & 공문
    │   ├── Contracts/     # 법무 검토 완료 계약 서류
    │   ├── Official_Docs/ # 수발신 공식 문서
    │   └── Financials/    # 예산안, 결산 보고서, 세무 서류
    │
    └── 04_Knowledge_Base/ # 조직 지식 자산
        ├── Form_Templates/# 부서 표준 양식 및 서식
        └── Research_Reports/# 시장 조사, 전략 보고서, 컨설팅 자료
```

## 4. 학생 / 연구자용 (Student & Researcher)
> 학기별/과목별 분류, 참고 논문 및 스크랩 자료 관리, 최종 제출본(_final_v2) 꼬임 방지하는 구조
- 파일 특징: 강의자료(PDF, PPT), 과제물, 논문, 연구 데이터, 성적/행정 서류

### Light
```text
Desktop/
└── Student_Workspace/
    ├── Classes/           # 현재 수강 중인 과목별 폴더
    ├── Assignments/       # 제출 예정 / 진행 중인 과제
    ├── Materials/         # 교재, 강의안 PDF, 참고 자료
    └── Archive/           # 지난 학기 수강 과목 보관소
```

### Standard
```text
Desktop/
└── Academic_Space/
    ├── 01_Current_Semester/# 이번 학기 수강 과목 (예: 2026-2)
    │   ├── Sub_Course_A/  # 과목 A (강의안, 과제, 시험 대비)
    │   └── Sub_Course_B/  # 과목 B (강의안, 과제, 시험 대비)
    │
    ├── 02_Team_Projects/  # 팀 프로젝트 및 조모임
    │   ├── Active/        # 현재 진행 중인 팀플 (모임록, 발표 자료, 제출본)
    │   └── Archive/       # 종료된 팀플
    │
    ├── 03_Research_Notes/ # 참고 자료 및 스터디
    │   ├── Papers_Read/   # 읽은 논문, 참고 문헌 PDF
    │   ├── Certs_Study/   # 자격증, 어학, 공모전 준비 자료
    │   └── References/    # 스크랩, 학술 자료, 데이터셋
    │
    └── 04_Career_Admin/   # 학적 및 취업 행정 서류
        ├── Admin_Docs/    # 재학증명서, 성적표, 장학 서류
        └── Resume_Portfolio/# 이력서, 자기소개서, 포트폴리오
```

### Professional
```text
Desktop/
└── Research_Environment/
    ├── 01_Thesis_Writing/ # 학위 논문 / 주요 저널 집필
    │   ├── Drafts/        # 논문 초안 (Draft_v1, Draft_v2)
    │   ├── Figures_Tables/# 논문용 그래프, 시각화 그림, 표
    │   └── Review_Comments/# 심사위원/지도교수 피드백 및 수정본
    │
    ├── 02_Experiments_Data/# 실험 및 데이터 분석
    │   ├── Raw_Data/      # 순수 원본 데이터셋 (보존 대상)
    │   ├── Processed/     # 정제/가공된 데이터 및 분석 코드 (.py, .R 등)
    │   └── Code_Scripts/  # 실험 실행 스크립트 및 시뮬레이션
    │
    ├── 03_Literature/     # 서지 및 논문 수집
    │   ├── To_Read/       # 읽어야 할 논문 (SmarTree 정돈 제안 대상)
    │   ├── Key_Papers/    # 핵심 인용 논문 (분야별 분류)
    │   └── Bib_Files/     # EndNote, Zotero, BibTeX 서지 파일
    │
    └── 04_Projects_Grants/# 연구 과제 및 학회
        ├── Rnd_Projects/  # 수행 중인 산학/국가 연구 과제 (보고서)
        └── Conferences/   # 학회 발표 자료, 포스터, 워크숍
```

## 5. 일반 / 캐주얼 사용자용 (General & Personal)
> 다운로드 폴더 자동 정리, 중복 사진/동영상 감지, 복잡하지 않고 직관적인 단순 분류 구조
- 파일 특징: 개인 사진/동영상, 수신한 파일, 금융/행정 PDF, 게임/유틸리티 설치 파일

### Light
```text
Desktop/
└── Personal_Space/
    ├── Documents/         # 개인 서류, 영수증, 안내문 PDF
    ├── Media/             # 사진, 동영상, 음악 파일
    └── Downloads_Clean/   # 다운로드받은 파일 중 보관할 것들
```

### Standard
```text
Desktop/
└── My_Workspace/
    ├── 01_Documents/      # 개인 행정 & 금융 & 생활 서류
    │   ├── Financial/     # 연말정산, 계좌/카드 서류, 영수증
    │   ├── Identity/      # 주민등록등본, 여권 사본, 계약서
    │   └── Medical/       # 진단서, 실비보험 청구 서류, 건강검진
    │
    ├── 02_Media_Photos/   # 개인 미디어 자산
    │   ├── Photos/        # 개인/가족 사진 (연도별/여행별)
    │   └── Videos/        # 개인 촬영 동영상 및 소장 미디어
    │
    ├── 03_Hobbies_Life/   # 취미 & 개인 관심사
    │   ├── Gaming/        # 게임 관련 파일, 모드(Mod), 스크린샷
    │   ├── Travel/        # 여행 계획, 항공권, 숙소 예약 내역
    │   └── Studies/       # 개인 자기계발, 읽을거리, 레시피
    │
    └── 04_Installers_Temp/# 임시 보관 및 설치 파일
        └── Setup_Files/   # 프로그램 설치 파일 (.exe, .msi - 주기적 정리 제안)
```

### Professional
```text
Desktop/
└── Personal_Archive/
    ├── 01_Finance_Legal/  # 자산 & 법무 & 행정 (중요 자산)
    │   ├── Tax_RealEstate/# 세금, 부동산, 자동차 관련 서류
    │   ├── Insurance_Bank/# 보험, 대출, 증권 관련 문서
    │   └── Identity_Docs/ # 인감, 신분 관련 서류
    │
    ├── 02_Life_Memories/  # 삶의 기록 & 미디어 아카이브
    │   ├── Digital_Photos/# 연도/월별 사진 아카이브
    │   ├── Home_Videos/   # 가족/개인 영상 아카이브
    │   └── Scraps_Journal/# 일기, 스크랩, 개인 소장 자료
    │
    ├── 03_Hobbies_Digital/# 디지털 취미 & 수집
    │   ├── Ebooks_PDFs/   # 소장 e-book, 잡지, 읽을거리
    │   ├── Music_Audio/   # 소장 음원 파일
    │   └── Game_Assets/   # 게임 세이브 파일, 패치, 모드
    │
    └── 04_Utility_Inbox/  # 유틸리티 & 시스템 정리소
        ├── Software_Tools/# 무설치 유틸리티, 드라이버
        └── Temporary/     # 정리 대기 중인 임시 파일
```