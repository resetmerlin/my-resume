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
- 토스 증권 앱 개별 종목 상세 화면 속 **주식 옵션 가격 예측기**, **옵션 포지션 수익 계산기** 기능 개발 <br/>(프론트 3명, 서버 2명, PO 1명, 프로덕트 디자이너 1명)

#### B. Overseas Platform Team(해외 주식 플랫폼 팀)
  금융 상품 출시 시, 운영팀이 내부 이슈 처리에 필요한 핵심 데이터와 도구에 접근할 수 있도록 **백오피스**를 개선 및 개발.
- **마진 거래 백오피스 개발**: 2024년 10월 31일 마진/외상거래 서비스 런칭 이전까지 전체 마진 거래 백오피스 화면 중 63%를 구현. <br/> (프론트 2명, 서버 3명, PM 2명)
- **달러 송금 백오피스 개발**: 2024년 12월 30일 달러 송금 서비스 런칭 이전까지 전체 달러 송금 백오피스 화면 구현. <br/> (프론트 1명, 서버 2명, PM 3명)

***해결한 주요 문제들***

1. 마진 거래 백오피스 UX 개선
   - 배경 및 문제: 운영팀이 외상(미정산) 사용자의 상환 순서를 수동으로 조정해야 하는 UX 문제
   - 해결안: **Drag & Drop 기반 순서 변경 UI를 도입**하여 운영팀의 업무 효율 향상에 기여.
3. 서버 드리븐 UI에 맞지 않는 인터페이스 대응
    - 배경 및 문제: 국내 서버에서 제공한 커서 방식(퍼포먼스 이슈)API가 기존 해외 주식 서버에서의 테이블을 그리기 위한 인터페이스와 불일치한 문제
    - 해결안: **커서 방식 API를 응용하여 기존 해외 주식 플랫폼 서버 드리븐 UI에 맞게** 구현. 추후 국내 서버와 협업할 경우를 대비해 추상화함.
4. 백오피스 특정 화면이 열리지 않는 문제: 
    - 배경 및 문제: 일부 사용자 환경에서 백오피스 화면이 로드되지 않는 현상 발생  
    - 원인 분석: lazy import를 통해 런타임으로 라우팅을 지정하는 과정에서 문제가 발생한 것으로 판단. 
    - 해결안: 화면 메타데이터를 활용해 **빌드 타임에 단일 번들로 통합**하고, **100개 이상의 JS 청크 요청을 1개로 축소**하여 성능 개선을 개선, 화면이 열리지 않는 문제도 해결

#### C. 토스증권 Page Transition 애니메이션 추가 검토 및 라이브러리 실험
- Vertical Weekly(프론트엔드 소모임) 회의에서 Page Transition 애니메이션 문제를 해결하기 위한 방안으로 당근마켓의 StackFlow 도입이 검토됨.
- 개인적으로 해당 라이브러리를 실험한 결과, Next.js 라우터 환경에서는 적용이 어려운 한계를 발견함  
- **직접 당근마켓 코어팀의 라이브러리 메인테이너와 만나 소통** 후 기술적 의문을 해소하고, 논의 결과를 팀과 공유하여, **도입 중단을 결정함에 기여**

# 창업

### Founder, Frontend Developer — EXCIVIS(2025.04 ~ 진행 중, 7개월)


AI와 Tutor와 함께하는 코딩 교육 플랫폼 [Runtric](https://runtric.com/) 프론트엔드 개발 <br/>
(프론트 1명, 서버 1명)

- 베타 런칭 (2025.08.04 ~ 2025.08.25): 250명 방문, 1,329 페이지뷰 달성, Retention 3%  
- 정식 런칭 (2025.10.13 ~ 2025.11.04): 3,643명 방문, 10,596 페이지뷰 달성. 독일 기술 매체 [t3n](https://t3n.de/news/programmieren-lernplattform-runtric-1712059/)에 소개되었으며,  
  전체 방문자의 **63%가 독일 국적**. Retention 15%


***미래 문제를 방지하기 위한 작업들***

1. 서비스 핵심 기능 로깅 시스템 구축  
   - 문제 및 배경: MVP 단계에서 유저의 핵심 기능 선호도를 파악하기 어려운 문제가 존재함, 즉 별도의 로깅 시스템이 없었음. 
   - 해결안: postHog(로깅 플랫폼)를 이용하여 **컴포넌트 기반 클라이언트 로깅 시스템을 설계함**. 또한 핵심 기능에 별도의 로깅 이름 및 인터페이스를 붙여 쉽게 구분할 수 있게 작업.
   - 성과 (1): 구축된 로깅 시스템을 통해 핵심 기능별 리텐션, 퍼널, 전환율 등 지표를 정량적으로 파악할 수 있게 됨, 향후 <ins>**[커스텀 마크다운 UI 개선], [비회원·회원 기능 확장]**</ins>의 근거가 될 수 있었음.
   - 성과 (2): 즉 지표를 통해 문제점을 좁힐 수 있었고 개선을 하여 초기 베타 런칭 **Retention을 3% 대비 정식 런칭 후 15%로 개선**할 수 있었음.
   
2. 개발 환경 분리 및 테스트,QA 환경 개선
    - 문제 및 배경: 프로덕션과 개발 환경이 분리되지 않으면 안정적인 서비스 운영과 효율적인 개발이 어려우며, QA 환경에서도 혼선이 발생함  
    - 해결안 (1): 클라이언트 플랫폼 담당으로서 서버 환경에 맞게 `Local, Alpha, Live` 환경을 구축. Alpha 환경에는 Admin API와 연동된 Tool을 추가해 QA 효율을 개선
    - 해결안 (2): Local 환경에서는 **Cloudflare Tunnel과 `local.runtric` DNS alias를 적용해 Next.js 로컬 환경을 맥 시뮬레이터와 연결하**여 모바일 유저도 대응할 수 있도록 함.
    - 성과: 안정적인 개발·운영  QA 효율 프로세스를 확보하고, **전체 방문자의 41%를 차지하는 모바일 유저의 서비스 참여율을 향상**시킴  

***마주한 주요 문제들***

1. 커스텀 마크다운 UI 개선  
    - 문제 및 배경: 베타 런칭 후 로깅 분석 결과, 챕터 페이지의 이탈률이 높음을 확인, 글만 존재하는 튜토리얼 콘텐츠가 문제임을 판단
    - 해결안: 글을 대신할 코드·카드·퀴즈 등 다양한 콘텐츠 타입을 통합 관리할 수 있는 Runtric 전용 커스텀 마크다운 모듈을 개발하고, 카드형 UI를 적용해 가시성과 몰입도를 강화함.  
    - 성과: 기존 전용 커스텀 마크다운 모듈화를 응용해 [Reddit 피드백(“튜토리얼이 너무 쉽다”)](https://www.reddit.com/r/websitefeedback/comments/1nu9xe2/comment/nhcn20i/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)의 피드백을(새 마크다운 UI) 빨리 반영할 수 있었으며 2주 내 정식 런칭 전에 반영할 수 있었음

2. 챕터 페이지 렌더링 지연 문제 해결  
   - 문제 및 배경: Runtric의 챕터 페이지는 서버로부터 전달받은 Markdown을 커스텀 UI로 변환하는 구조로, JS 청크가 커지고 렌더링 대기 시간이 발생할 수 있었음  
   - 해결안: **SSG를 적용해 튜토리얼을 빌드 타임에 HTML로 프리렌더링**하고, 동기화를 위해 전체 재빌드 대신 **Next.js SSR을 활용해 런타임에서 API 기반 HTML 렌더링**을 수행함  
   - 성과 (1): 미리 빌드된 HTML이 서버 데이터와 불일치하여 **404 fallback 페이지로 이동하던 문제를 방지**함  
   - 성과 (2): 정식 런칭때 예기치 못한 해외 트래픽(예: 독일 지역)에서도 API 호출 전 **사전 빌드된 HTML을 즉시 전달**할 수 있게 함

    
3. 비회원·회원 기능 확장  
   - 문제 및 배경: 베타 런칭 후 로깅 분석 결과, 회원가입 없이 이탈하는 사용자가 많아 핵심 기능에 대한 이용 성향과 선호도를 정확히 파악하기 어려웠음  
   - 해결안 (1): 기존 회원 전용 서비스를 비회원도 이용할 수 있도록 **OAuth2 인증 시스템을 확장**하고, 단일 API Client 모듈에 회원·비회원 기반 **토큰 재검증 로직**을 추가함  
   - 해결안 (2): 인증 토큰을 **인메모리에 저장해 추출을 방지**하고, **Worker Thread를 통해 인증 API를 별도 스레드에서 안전하게 갱신**하도록 설계함  
   - 성과: 정식 런칭때 2,500명 이상이 회원가입 없이 핵심 기능을 이용할 수 있었으며, 제품 이탈 원인을 회원가입 과정 때문이 아닌 **기능 사용도 기반으로 분석할 수 있는 환경을 구축함**


## 사이드 프로젝트

#### [Mitmar'd DB](https://github.com/talmid-mitmared/mitmar-d-DB/tree/chunk/btree) - Frontend(2025.04 ~ 진행 중)

- 문제 및 배경: 파일·폴더 검색 효율을 높이기 위해 개인용 데스크톱 DB를 개발하면서 TypeScript로 B-tree(Insert, Search, Delete) 인덱싱 알고리즘을 직접 구현함. 구현 과정에서 재귀 기반 트리 구조에서 참조(Mutability) 문제가 발생함  
- 해결안: [React Fiber 접근 방식](https://github.com/facebook/react/issues/7942)을 참고해 재귀대신 `do-while` 반복 구조로 변경 후 참조 불안정 문제를 해결하고, 안정적인 노드 순회 로직을 완성함

---


### 기타
* [YouTube 기술 콘텐츠 제작](https://youtube.com/@merlinsdevelopmentjourne-og7fp?si=F-NDYskcGBZJX-lj): 토스증권 근무 초기, 피드백받은 커뮤니케이션 문제를 개선하기 위해 매일 학습한 기술 개념을 YouTube에 설명 형식으로 업로드함. 이를 통해 커뮤니케이션 및 설명 역량을 강화했으며, 마진 거래 백오피스와 달러 송금 백오피스 서비스 완성에 기여함  
* 경동초등학교 코딩 봉사 (2025.10 ~ 2025.11): 기존 Scratch 커리큘럼이 학생 수준(4학년)과 맞지 않아, Python 기초 교육 과정을 직접 구성해 진행함. 설치 없이 웹 환경에서 변수와 입출력 등 Python 문법을 활용해 학생들이 자신의 이름과 값을 개인 웹사이트에 넣을 수 있도록 지도함. 마지막 날 1교시 반 만에 전원이 완성 목표를 달성했으며, 학생들의 코딩 입문에 대한 부담과 편견을 해소시킴


### 학력 및 자격

* 단국대학교 소프트웨어학과 (B.Sc.): 2021 ~ 현재 재학 중


### 기술 스택 (Technologies & Languages)

* **언어:** ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
* **기술:** ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white) ![React Query](https://img.shields.io/badge/React%20Query-FF4154?logo=reactquery&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) ![Turborepo](https://img.shields.io/badge/Turborepo-000000?logo=turborepo&logoColor=white), ![SCSS](https://img.shields.io/badge/SCSS-CC6699?logo=sass&logoColor=white)





