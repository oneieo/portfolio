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
      username: admin
    design:
      # Hugo date format
      date_format: "January 2006"
      # Education or Experience section first?
      is_education_first: false

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
