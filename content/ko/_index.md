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

  - block: slider
    content:
      slides:
        - title: 글로벌 무역 전문가
          content: 국경을 넘어 기회를 발굴하고, 한국 기업과 세계를 연결하는 가교
          align: center
          background:
            image:
              filename: public-domain-vectors-LlhAZH8rvVY-unsplash.jpg
              filters:
                brightness: 0.7
            position: center
            color: "#666"

        - title: 프론트엔드 개발자
          content: 사용자 경험을 최우선으로, 혁신적인 웹 솔루션을 설계하고 구현
          align: center
          background:
            image:
              filename: boitumelo-viS6-ja0dCw-unsplash.jpg
              filters:
                brightness: 0.7
            position: center
            color: "#555"

        - title: 무한한 가능성
          content: 통찰력과 창조성으로, 글로벌 디지털 비즈니스의 미래를 만들어가다
          align: center
          background:
            image:
              filename: compare-fibre-9HGPvHThNME-unsplash.jpg
              filters:
                brightness: 0.7
            position: center
            color: "#444"
    design:
      slide_height: "400px"
      is_fullscreen: false
      loop: true
      interval: 2500

  - block: collection
    content:
      title: 박람회 참가
      filters:
        folders:
          - exp_gtep
      count: 3
    design:
      view: custom-card-1
      columns: "3"

  - block: collection
    content:
      title: 프로젝트
      filters:
        folders:
          - project
      count: 3
    design:
      view: custom-card-2
      columns: "3"

  - block: collection
    id: projects
    content:
      title: 기술스택
      filters:
        folders:
          - skills
      default_button_index: 0
      buttons:
        - name: All
          tag: "*"
    design:
      view: showcase
      columns: "1"

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

  - block: markdown
    content:
      title: ""
      text: |
        # 🏆 수상

  - block: awards
    content:
      title: 수상
      username: admin
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
