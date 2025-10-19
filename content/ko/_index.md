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
        color: "#FFDCE9"
        text_color_light: false

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

            국제 무역의 이론적 기반과 실무 지식을 습득하고, 글로벌 시장 동향 분석, 무역 협상, 수출입 절차, 국제 마케팅 전략 등을 학습하여 글로벌 비즈니스 전문가로서 성장했습니다.

        - title: 컴퓨터공학 복수전공
          company: 전북대학교 공과대학
          company_url: "https://csai.jbnu.ac.kr/csai/index.do"
          location: 전주, 대한민국
          date_start: "2022-09-01"
          date_end: ""
          description: |
            평점: 4.0/4.5

            컴퓨터 과학의 기초 이론부터 실무 응용까지 학습하며, 프로그래밍, 자료구조, 알고리즘, 데이터베이스, 인공지능 등을 통해 혁신적인 소프트웨어 솔루션을 개발하는 능력을 키웠습니다.
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

  - block: contact
    id: contact
    content:
      title: 연락처
      email: boywonderof@jbnu.ac.kr
      address:
        city: Jeonju
        region: Jeollabuk-do
        country: South Korea
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: "https://www.linkedin.com/in/%EC%A7%80%EC%9B%90-%EC%84%A0-467467366/"
    design:
      columns: "2"
---
