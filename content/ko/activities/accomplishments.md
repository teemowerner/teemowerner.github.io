---
# An instance of the Accomplishments widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: accomplishments

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

# Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
title: 'Accomplish&shy;ments'
subtitle:

# Date format
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
item:
  - date_end: ''
    date_start: '2023-09-25'
    description: '2023년 2학기 부스트 코스 프로젝트로 진행한 `할랄 음식지도`는 서울에서 할랄 식품을 찾고 이용할 수 있는 웹 애플리케이션으로, Streamlit 프레임워크를 사용하여 개발되었습니다. 이 애플리케이션은 사용자가 지도 상에서 할랄 음식점을 검색하고 정보를 얻을 수 있어 할랄 식단을 찾는 외국인에게 유용한 주었습니다.

네이버 지도 또는 카카오 지도로 키워드 검색 시 구글맵보다 성능이 현저하게 떨어지고, 영어로 식당을 검색하였을 때 정확도가 낮다는 문제점이 있습니다. 이는 한국에서는 상권 정보를 등록할 때 한국어로 상표를 등록해야 하기 때문에, 케밥 레스토랑의 고객 대부분인 한국어를 할 줄 모르는 외국인이 할랄 음식점을 찾을 때 어려움이 있음을 확인하였습니다.

이러한 문제점을 해결하기 위해, 소상공인시장진흥공단 데이터를 이용하여 할랄 음식점 정보를 수집하고, 이를 pandas를 이용하여 새로운 column인 "할랄"을 만들고 음식점들을 지도 위에 표현하였습니다.
이를 통해 할랄 음식점 정보를 더욱 정확하게 수집하고, 영어로 된 음식점 정보를 수집하여, 외국인 사용자들이 더욱 쉽게 할랄 음식점을 찾을 수 있도록 하였습니다.
'
    organization: 네이버
    organization_url: https://www.naver.com
    title: Neural Networks and Deep Learning
  - certificate_url: https://www.edx.org
    date_end: ''
    date_start: '2021-01-01'
    description: Formulated informed blockchain models, hypotheses, and use cases.
    organization: edX
    organization_url: https://www.edx.org
    title: Blockchain Fundamentals
    url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  - certificate_url: https://www.datacamp.com
    date_end: '2020-12-21'
    date_start: '2020-07-01'
    description: ''
    organization: DataCamp
    organization_url: https://www.datacamp.com
    title: 'Object-Oriented Programming in R'
    url: ''

design:
  columns: '1'
---
