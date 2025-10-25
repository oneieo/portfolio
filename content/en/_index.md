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
      title: Introduction
      username: admin
    design:
      background:
        color: "#FFF3F7"
        text_color_light: false

  - block: slider
    content:
      slides:
        - title: Global Trade Expert
          content: Discovering opportunities beyond borders, bridging Korean businesses with the world
          align: center
          background:
            image:
              filename: sean-oulashin-KMn4VEeEPR8-unsplash.jpg
              filters:
                brightness: 0.7
            position: center
            color: "#666"

        - title: Frontend Developer
          content: Designing and implementing innovative web solutions with user experience as top priority
          align: center
          background:
            image:
              filename: jonathan-francisca-Y9FvnY7FU1A-unsplash.jpg
              filters:
                brightness: 0.7
            position: center
            color: "#555"

        - title: Infinite Possibilities
          content: Creating the future of global digital business with insight and creativity
          align: center
          background:
            image:
              filename: javier-allegue-barros-C7B-ExXpOIE-unsplash.jpg
              filters:
                brightness: 0.7
            position: center
            color: "#444"
    design:
      slide_height: "300px"
      is_fullscreen: false
      loop: true
      interval: 3000

  - block: collection
    id: projects
    content:
      title: Tech Stack
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

  - block: collection
    content:
      title: Projects
      filters:
        folders:
          - project
      count: 3
    design:
      view: custom-card-2
      columns: "2"

  - block: collection
    content:
      title: Trade Fair Participation
      filters:
        folders:
          - exp_gtep
      count: 3
    design:
      view: custom-card-1
      columns: "2"

  - block: experience
    content:
      title: Education
      date_format: Jan 2006
      items:
        - title: ✈️ International Trade Major
          company: College of Business Administration, JBNU
          company_url: "https://trade.jbnu.ac.kr/trade/index.do"
          location: Jeonju, South Korea
          date_start: "2021-03-01"
          date_end: ""
          description: |
            GPA: 4.25/4.5

            Acquiring theoretical foundations and practical knowledge of international trade, learning global market trend analysis, trade negotiations, import/export procedures, and international marketing strategies to grow as a global business professional.

        - title: 💻 Computer Engineering (Double Major)
          company: College of Engineering, JBNU
          company_url: "https://csai.jbnu.ac.kr/csai/index.do"
          location: Jeonju, South Korea
          date_start: "2022-09-01"
          date_end: ""
          description: |
            GPA: 4.0/4.5

            Learning from fundamental theories to practical applications in computer science, developing the ability to create innovative software solutions through programming, data structures, algorithms, databases, and artificial intelligence.
    design:
      columns: "2"

  # Career Section
  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: 💻 Frontend Developer
          company: NearDeal
          company_url: ""
          location: ""
          date_start: "2025-09-07"
          date_end: ""
          description: |
            - Developed responsive user interfaces using React and Next.js
            - Implemented state management and API integration
            - Optimized application performance and enhanced user experience

        - title: 👩🏻‍💼 GTEP Agent
          company: JBNU GTEP Business Group
          company_url: "https://jbnugtep.com/"
          location: Jeonju, South Korea
          date_start: "2024-12-24"
          date_end: "2025-12-31"
          description: |
            - Supported global export activities and trade consulting for Korean SMEs
            - Identified and matched overseas buyers, conducted export market research and analysis
            - Assisted with trade documentation and import/export procedures
            - Planned and supported global business networking events

        - title: 📢 Interpreter & Export Marketer
          company: BeautyWorld Saudi Arabia 2025
          company_url: ""
          location: Saudi Arabia
          date_start: "2025-04-21"
          date_end: "2025-04-23"
          description: |
            - Supported Korean cosmetics companies' market entry into Saudi Arabia
            - Provided on-site business interpretation and buyer consultation support
            - Developed export marketing strategies and identified local buyers
            - Assisted with product presentations and contract negotiations
    design:
      columns: "2"

  - block: markdown
    content:
      title: ""
      text: |
        # Awards

  - block: awards
    content:
      title: Awards
      username: admin
    design:
      columns: "2"

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ""
      text: ""
      email: boywonderof@jbnu.ac.kr
      phone: ""
      address:
        street: 567 Baekje-daero, Deokjin-gu
        city: Jeonju-si
        region: Jeonbuk State
        postcode: "54896"
        country: South Korea
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
