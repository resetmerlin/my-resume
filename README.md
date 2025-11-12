# 소개

**사용자 중심의 웹 서비스를 개발하는 프론트엔드 엔지니어** 조동준입니다.
실제 프로젝트 경험을 통해 **문제 해결 능력**과 **최신 기술을 효과적으로 적용하는 역량**을 길렀습니다.
지속적인 학습과 협업을 통해 성장하는 것을 목표로 하고 있습니다.
영어에 능통하여 기술적 개념을 효율적으로 커뮤니케이션할 수 있습니다.

📧 [resetmerlin@gmail.com](mailto:resetmerlin@gmail.com)
🔗 [LinkedIn](http://www.linkedin.com/in/merlin-jo-79428a272) | [GitHub](https://github.com/resetmerlin) | [YouTube](https://youtube.com/@merlinsdevelopmentjourne-og7fp?si=F-NDYskcGBZJX-lj) 

# 경력

### Frontend Developer Assistant (Contract) — 토스 증권(2024.04 ~ 2024.12, 9개월)
*@ US Option Silo, Overseas Platform Team*

#### A. Option Silo Team(옵션 사일로 팀)
  토스증권 앱(WebView 기반 MTS) 내 옵션 상품 관련 기능 개발 담당.

주요 참여 제품들
- 토스 증권 앱 개별 종목 상세 화면 속 **주식 옵션 가격 예측기**, **옵션 포지션 수익 계산기** 기능 개발(프론트 2명, 서버 2명, PO 1명, 프로덕트 디자이너 1명)

#### B. Overseas Platform Team(해외 주식 플랫폼 팀)
  금융 상품 출시 시, 운영팀이 내부 이슈 처리에 필요한 핵심 데이터와 도구에 접근할 수 있도록 **백오피스** 를 개선 및 개발.
  
주요 참여 제품들
- **마진 거래 백오피스 개발**(프론트 2명, 서버 3명, PM 2명): 2024년 10월 31일 마진거래 서비스 런칭 이전까지 전체 마진 거래 백오피스 화면 중 63%를 구현.
- **달러 송금 백오피스 개발**(프론트 1명, 서버 2명, PM 3명): 2024년 12월 30일 달러 송금 서비스 런칭 이전까지 전체 달러 송금 백오피스 화면 구현.

해결한 주요 문제들
1. 마진 거래 백오피스 UX 개선
    - 배경 및 문제: 운영팀이 외상(미정산) 사용자의 상환 순서를 수동으로 조정해야 하는 UX 문제
    - 해결 안: **Drag & Drop 기반 순서 변경 UI로 개선**하여 운영팀의 업무 효율 향상에 기여.
2. 서버 드리븐 UI에 맞지 않는 인터페이스 대응
    - 배경 및 문제: 기존 해외 주식 서버에서의 테이블을 그리기 위한 서버 드리븐 인터페이스가 국내 서버에서 퍼포먼스 이슈로 커서 방식 API를 줘 기존 UI와 인터페이스 불일치한 문제
    - 해결 안: 커서 방식 API를 응용하여 기존 해외 주식 플랫폼 서버 드리븐 UI에 맞도록 추상화, 요건에 맞는 UI를 그림. 추후 이런 문제를 대비해 국내 서버와 협업할 경우를 대비하여 재사용할 수 있도록 추상화함.
3. 백오피스 특정 화면이 열리지 않는 문제: 
    - 배경 및 문제: 백오피스 화면이 얘기치 않게 소수의 인원만 열리지 않는 문제가 발생.
    - 해결 안(1): 초기에는 SPA 구조 환경 아래 lazy import로 런타임에서 화면 폴더를 읽은 후 페이지 라우트들을 지정하여 런타임 의존성으로 인해 안정성이 떨어진 것으로 판단.
    - 해결 안(2): 화면 폴더 안 화면 메타데이터를 사용해 빌드 타임에 단일 빌드 파일로 통합으로써 **100개 이상의 JS 청크 HTTP 요청을 하나로 축소하여 성능 개션** 및, **화면이 열리지 않는 문제도 해결**.
      
#### C. 토스 증권 Page Transition 애니메이션 추가 검토 및 라이브러리 실험

토스 증권 서비스 내 Page Transition 시 애니메이션을 추가하려는 논의가 지속적으로 이어졌으나, 웹 퍼포먼스 이슈로 인해 중단되어있었음. 이후 Vertical Weekly(프론트 개발자들과 가지는 정기 소모임 회의) 회의에서 당근마켓의 자체 개발 라이브러리인 StackFlow를 도입하는 방안이 제시됨

해결한 주요 문제들
1. StackFlow와 현재 토스 증권 웹 뷰 프론트 환경이랑 불일치하다는 방향성 확립에 기여
    - 배경 및 문제: StackFlow 라이브러리를 혼자 실험해본 결과, Next.js 라우터 환경에서는 사용이 어려운 문제가 있음을 발견.
    - 해결 안: 해당 문제에 대한 의문이 생겨 직접 당근 코어에 재직 중인 라이브러리의 메인테이너를 직접 찾아가 관련 궁금증을 해소한 후 논의 결과를 바탕으로 팀과 다시 논의했으며, 최종적으로 StackFlow 라이브러리 도입은 리스크가 문제로 인해 중단하기로 결정

# 창업

## Founder, Frontend Developer — EXCIVIS(2025.04 ~ 2025.11, 7개월)

- 베타 런칭(2025년 8월 04일 ~ 2025년 8월 25일): 250명 1,329 페이지뷰 달성
- 정식 런칭(2025년 10월 13일 ~ 2025월 11월 4일): 3,643명 10,596 페이지뷰 달성, 독일 기술 매체 **t3n**에 소개되었으며, **전체 방문자의 63%가 독일 국적**. [t3n 기사 보기](https://t3n.de/news/programmieren-lernplattform-runtric-1712059/)

#### A. Runtric Lean Team(런트릭 린 팀)
AI와 Tutor와 함께하는 코딩 교육 플랫폼 [Runtric](https://runtric.com/) 프론트엔드 개발

미래 문제를 방지하기 위한 작업들
1. 서비스 핵심 기능에 대한 로깅 시스템 구축
   - 문제 및 배경: postHog(로깅 플랫폼) 사용 결과 자동으로 유저 행동 캡쳐하는 것의 데이터가 너무 많음, 또한  MVP 제품이 유저에게 선택받고 핵심 기능에 대한 선호도를 파악할 수 없던 문제 존재.
   - 해결 안(1): 컴포넌트 단위 로깅 데이터에 `Feature`, `Navigation`, `Fallback` 세 카테고리를 넣어 클라이언트 이벤트 로깅 시스템을 설계. postHog를 응용하여 수동 커스텀 이벤트 훅을 생성
   - 해결 안(2): 해결 안(1)을 응용해 독자적 로깅 이름 룰을 입혀 **기능 사용기반으로 유저들의 리텐션을 분석** 할 수 있도록 구조화함
   - 성과: 베타 런칭 이후 방문 후 이탈률이 매우 높고 전체 방문자 중 약 10%만 회원가입을 완료한 문제를. 위 해결안(1), (2)을 통해 만들어진 로깅 시스템으로 이탈 원인 파악할 수 있었음.
   - 성과: MVP 런칭 이후 핵심 기능에 따른 리텐션, 퍼널 지표, Active Users Cont, Converation Rate등 주요 지표 파악 가능해짐,
   - 성과: 이에 비회원도 콘텐츠를 사용할 수 있도록 클라이언트 OAuth2 세션 플로우를 확장하고, 비회원/회원 UI를 분리함을 통해 정식 서비스 런칭때 3,643명이 회원가입 없이 사용할 수 있도록 하여 회원가입으로 필수로 인한 이탈률이 아닌 제품 기능 본연 자체의 이탈율 및 지표를 더 쌓을 수 있게 하였음
   
2. 개발, QA 환경에 맞게 분리 작업 
    - Production과 Development 환경이 분리되어야 안정성있는 서비스 및 개발할때도 빠름
    - Client와 Server 모두 **Local / Alpha / Live 환경**을 분리하여 독립적인 환경을 구축하였음(클라 담당).
    - Alpha 환경에는 Admin API와 연결된 Admin Tool을 만듬으로써 **QA 효율을 개선**.
    - local 환경에서는 Cloudflare Tunnel과 `local.runtric` DNS alias를 응용해 Next.js 로컬 환경을 맥 시뮬레이터와 연결하도록 설졍함. 모바일 유저(전체 방문자 중 41%)도 대응할 수 있게 하여 기능 사용 참여율을 높임.

3. Static Site Generation (SSG) 및 Server Side Rendering (SSR) 활용
    Runtric 내 챕터 페이지는 서버 드리븐 구조로 Markdown을 커스텀 UI로 변환하기 때문에 런타임 JS 청크가 큼(@TODO, 대략적인 수치 필요).
      - 런타임 렌더링 시 싱글 스레드 환경 특성상 그 이후 기다리는 렌더링 리소스들이 기다려야하는 발생할 수 있어, **SSG를 통해 빌드 타임에 튜토리얼을 HTML로 프리렌더링**하도록 변경. 이를 통해 예상치 못한 트래픽(예: 독일 지역)에서도 빠른 html 전달을 유지할 수 있엇었음.
      - 튜토리얼이 서버에서 생성될 때마다 전체 빌드를 요구하던 문제를 Next.js SSR도 응용하여, **404 fallback 대신 서버 런타임에 API 호출로 HTML을 동기화 및 렌더링**하도록 하면서 문제를 해결함.

마주한 주요 문제들
1. 커스텀 마크다운 UI
    - 베타 런칭 후 로깅 시스템 분석 결과 챕터 페이지 이탈률 증가 파악, 글 만 있는 튜토리얼 콘텐츠가 문제임을 파악함
    - 글을 대신할 커스텀 카드 UI를 추가하여 가시성과 몰입도를 높임, 코드·카드·퀴즈 등 다양한 콘텐츠 타입을 하*Runtric 전용 마크다운 라이브러리**처럼 추상화하여 하나의 단일 모듈로 관리할 수 있도록 함.
    - [Reddit에서 올린 피드백을](https://www.reddit.com/r/websitefeedback/comments/1nu9xe2/comment/nhcn20i/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) 통해 튜토리얼 내용이 너무 쉽다는 피드백을 받은 후 해당 모듈을 이용함으로써 2주 안에 기능을 개발할 수 있었으며 추후 정식 런칭때 3,643명이 방문할 당시 많은 유저가 사용한 지표이기도 하고 재방문률 증가함(지표 필요).
    - 글을 대신할 커스텀 카드 UI를 추가하여 가시성과 몰입도를 높임으로써 추후 정식 런칭때 3,643명이 회원가입 없이 사용할 수 있게 만들어 기능 보완점을 찾아낼 수 있었음.

2. 환경 분리로 인한 크롤링 문제 및 이미지 리소스 문제
    - 환경 분리로 인해 알파 클라이언트 웹 사이트를 구글 봇이 클롤링할 수 있었음.
    - 빌드 스크립트를 통해 환경별(local, alpha, live) 자동 `robots.txt` 생성을 적용하여 비프로덕션 환경의 크롤링을 차단하고, `sitemap.xml`도 빌드 시 자동 생성하여 해결함.
    - 더 나아가서 빌드 단계에서 스크립트를 이용해 서비스 내 이미지 파일을 압축하고, 이 압축된 파일을 기준으로 해싱을 적용하여 빌드시마다 똑같은 이미지에 대한 작업을 방지함 및 해싱된 이미지 리소스들에 대한 캐시컨트롤을 입혀 웹 성능도 최적화함.

3. 비회원/회원에 대응해야 하는 서비스 기획 변경(작성중...)


---

## 사이드 프로젝트

### [WebOs](https://github.com/resetmerlin/Web-OS/tree/main) - Frontend(@TODO, 너무 과함. 삭제가 필요할 수도?)
**2025년 12월 ~ 2025년 2월**
퇴사 전 피드백 받은 CS 지식을 보완하기 위해 시작, OS 공부 중 컴퓨터 아키텍처의 중요성을 깨달은 후 잊어버리지 않기 위해 typescript로 Web OS를 만들려는 시도
1. x86, fetch-decode-execute cycle 및 bus와 비슷하게 웹 CustomEvent를 응용해 생성
2. Real Mode, Long Mode에 맞게 bit 사이즈 설정하여 Program Counter와 Offeset 값을 이용하여 다음 Instruction을 가져오는 로직 생성

---

## 기타 (Etc)

* YouTube 기술 콘텐츠 제작
  *   토스 증권 근무 초기 피드백받은 커뮤니케이션 문제를 해결하기 위해 매일 공부한 기술 개념과 학습 내용을 YouTube에 설명하듯이 업로드하였음.
  이를 통해 커뮤니케이션 및 설명 역량을 강화하였으며, 이는 마진 거래 백오피스, 달러 송금 백오피스 서비스 완성에 기여함.

* 경동초등학교 코딩 봉사(2025-10~11)
  *   기존 커리큘럼 Scratch가 있었으나, 이미 학생들은(4학년) 1학기때 배웠기도 하고 해당 커리큘럼이 학생들에게 이롭지 않다고 판단. 파이썬을 가르쳐 준 후 마지막 시간에 설치 없이 가르친 지식을 통해 학생들로 하여금 웹 사이트에 파이썬 변수 할당등을 이용해 파이썬을 응용하여 개인 웹 사이트를 만들 수 있도록 도와줌. 이를 통해 1교시 반만에 모든 학생들이 요구 사항에 맞게 만들 수 있도록 하였음. 즉 학생들에게 코딩 입문에 대한 부담 및 편견을 해소시킴


---

## 학력 및 자격 (Education & Certifications)

* **단국대학교 컴퓨터공학과 (B.Sc.)**
  2021 ~ 현재 재학 중

---

## 기술 스택 (Technologies & Languages)

* **언어:** ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
* **기술:** ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white) ![React Query](https://img.shields.io/badge/React%20Query-FF4154?logo=reactquery&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) ![Turborepo](https://img.shields.io/badge/Turborepo-000000?logo=turborepo&logoColor=white), ![SCSS](https://img.shields.io/badge/SCSS-CC6699?logo=sass&logoColor=white)














