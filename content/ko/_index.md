---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: about.avatar
    id: about
    content:
      title: 소개
      username: admin
    design:
      background:
        color: "#FFF3F7"
        text_color_light: false

  - block: collection
    content:
      title: 박람회 참가
      filters:
        folders:
          - exp_gtep
      count: 3
    design:
      view: custom-card-1
      columns: "2"

  - block: collection
    content:
      title: 프로젝트
      filters:
        folders:
          - project
      count: 3
    design:
      view: custom-card-2
      columns: "2"

  - block: experience
    content:
      title: 학력
      date_format: Jan 2006
      items:
        - title: 무역학 전공
          company: 전북대학교 경상대학
          company_url: "https://trade.jbnu.ac.kr/trade/index.do"
          location: 전주, 대한민국
          date_start: "2021-03-01"
          date_end: ""
          description: |
            평점: 4.25/4.5

            국제 무역의 이론적 기반과 실무 지식을 습득하고, 글로벌 시장 동향 분석, 무역 협상, 수출입 절차, 국제 마케팅 전략 등을 학습하여 글로벌 비즈니스 전문가로서 성장하고 있습니다.

        - title: 컴퓨터공학 복수전공
          company: 전북대학교 공과대학
          company_url: "https://csai.jbnu.ac.kr/csai/index.do"
          location: 전주, 대한민국
          date_start: "2022-09-01"
          date_end: ""
          description: |
            평점: 4.0/4.5

            컴퓨터 과학의 기초 이론부터 실무 응용까지 학습하며, 프로그래밍, 자료구조, 알고리즘, 데이터베이스, 인공지능 등을 통해 혁신적인 소프트웨어 솔루션을 개발하는 능력을 키우고 있습니다.
    design:
      columns: "2"

  # 경력 섹션
  - block: experience
    content:
      title: 경력
      date_format: Jan 2006
      items:
        - title: 프론트엔드 개발자
          company: NearDeal
          company_url: ""
          location: ""
          date_start: "2025-09-07"
          date_end: ""
          description: |
            - React 및 Next.js를 활용한 반응형 사용자 인터페이스 개발
            - 상태 관리 및 API 연동 구현
            - 애플리케이션 성능 최적화 및 사용자 경험 개선

        - title: GTEP 요원
          company: 전북대학교 GTEP 사업단
          company_url: "https://jbnugtep.com/"
          location: 전주, 대한민국
          date_start: "2024-12-24"
          date_end: "2025-12-31"
          description: |
            - 대한민국 중소기업의 글로벌 수출 활동 지원 및 무역 상담
            - 해외 바이어 발굴 및 매칭, 수출 시장 조사 및 분석
            - 무역 서류 작성 지원 및 수출입 절차 안내
            - 글로벌 비즈니스 네트워킹 행사 기획 및 운영 지원

        - title: 통역 및 수출마케터
          company: BeautyWorld Saudi Arabia 2025
          company_url: ""
          location: 사우디아라비아
          date_start: "2025-04-21"
          date_end: "2025-04-23"
          description: |
            - 한국 화장품 기업의 사우디아라비아 시장 진출 지원
            - 현장 비즈니스 통역 및 바이어 상담 지원
            - 수출 마케팅 전략 수립 및 현지 바이어 발굴
            - 제품 프레젠테이션 및 계약 협상 지원
    design:
      columns: "2"

  - block: collection
    id: projects
    content:
      title: 프로젝트
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: "*"
    design:
      view: showcase
      columns: "1"

  - block: awards
    content:
      title: 수상
      items:
        - title: 총장상_성적우수상
          date: "2022-03-15"
          awarder: 전북대학교 총장
          icon: trophy
          summary: |
            2학년 재학 기간 동안 전 과목 평균 평점 4.5/4.5를 유지하여 학과 1등을 달성하였으며, 이러한 학업적 성취를 인정받아 총장상을 수상하였습니다.

        - title: 최우수상_2025학년도 1학기 SW 캡스톤디자인 경진대회
          date: "2025-06-20"
          awarder: 전북대학교
          icon: trophy
          summary: |
            "LLM을 활용한 AI 논문 요약 및 시각화 플랫폼"을 주제로 프로젝트를 진행하였으며, 대규모 언어 모델의 자연어 처리 기술을 활용하여 학술 논문의 핵심 내용을 자동으로 추출하고 직관적인 시각화 자료로 변환하는 혁신적인 시스템을 개발하였습니다. 연구자들의 논문 검토 시간을 획기적으로 단축시킬 수 있는 실용적인 솔루션을 제시하였고, 우수한 기술적 완성도와 높은 활용 가능성을 인정받아 최우수상을 수상하였습니다.

        - title: 최우수상_2025 대학생 무역캠프
          date: "2025-08-29"
          awarder: 한국무역협회(KITA)
          icon: trophy
          summary: |
            한국무역협회와 산학협동재단이 공동으로 주관한 2025 무역 시뮬레이션 경진대회에서 한국 츄르 기업의 일본 시장 진출 전략을 주제로 발표하였습니다. 일본 반려동물 시장의 성장 추세와 소비자 선호도를 면밀히 분석하고, 한국 제품의 차별화된 경쟁력을 기반으로 한 현지화 전략, 유통 채널 구축 방안, 마케팅 전략 등을 체계적으로 수립하여 실현 가능성 높은 시장 진출 계획을 제시하였습니다. 시장 조사의 깊이, 전략의 구체성, 그리고 실무 적용 가능성을 인정받아 최우수상을 수상하였습니다.
    design:
      columns: "2"

  - block: contact
    id: contact
    content:
      title: 연락처
      subtitle: ""
      text: ""
      email: boywonderof@jbnu.ac.kr
      phone: ""
      address:
        street: 덕진구 백제대로 567
        city: 전주시
        region: 전북특별자치도
        postcode: "54896"
        country: 대한민국
        country_code: KR
      coordinates:
        latitude: "35.8468"
        longitude: "127.1294"
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: "https://www.linkedin.com/in/%EC%A7%80%EC%9B%90-%EC%84%A0-467467366/"
        - icon: github
          icon_pack: fab
          name: GitHub
          link: "https://github.com/oneieo"
        - icon: instagram
          icon_pack: fab
          name: Instagram
          link: "https://www.instagram.com/oneieo"
      autolink: true
    design:
      columns: "2"
---
