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
        color: yellow
        text_color_light: false

  - block: experience
    content:
      title: 학력
      date_format: Jan 2006
      items:
        - title: PhD in Artificial Intelligence
          company: Stanford University
          company_url: "https://www.stanford.edu"
          location: California
          date_start: "2010-09-01"
          date_end: "2012-06-01"
          description: ""
        - title: MEng in Artificial Intelligence
          company: Massachusetts Institute of Technology
          company_url: "https://www.mit.edu"
          location: Massachusetts
          date_start: "2008-09-01"
          date_end: "2009-06-01"
          description: ""
        - title: BSc in Artificial Intelligence
          company: Massachusetts Institute of Technology
          company_url: "https://www.mit.edu"
          location: Massachusetts
          date_start: "2005-09-01"
          date_end: "2008-06-01"
          description: ""
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
