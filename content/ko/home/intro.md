---
# Use the Intro widget of the Blog template
widget: about.avatar

# This file represents a page section.
headless: true

# Order that this section will appear in.
weight: 10

author: admin
#design:
#  background:
#    color: '#090a0b'
#    text_color_light: true
#    video:
#      path:  # enter filename of a video in /assets/media
#  css_class: fullscreen
---

👋 산업공학 **김동건**, 
{style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}

pdf 이력서를 다운받으실 수 있습니다. [이력서 다운 받으러가기](/about/) 😍

---

# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">MacsLAB에서는 의료, EMR, Vision, 항공, 국방 등 여러 분야에 AI 및 딥러닝을 활용한 연구를 수행하고 있으며, 의료 수학 및 AI 기반 연구도 함께 수행하고 있습니다. 뿐만 아니라, 풀스택 개발 및 AI를 활용한 어플리케이션 개발 등 Development & Deploy하는 실용적인 분야에도 집중하고 있습니다.</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">Medical AI</span>
        content: <span style="font-size:90%">의료AI를 통한 질병 진단 및 환경 개선</span>
        align: center
        background:
          image:
            filename: medical.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Mathematics</span>
        content: <span style="font-size:90%">AI와 관련된 수학 및 최적화 이론 연구</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Recruit</span>
        content: <span style="font-size:90%">Interested in MacsLAB?</span>
        align: center
        background:
          image:
            filename: recruitment.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: contact

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
---