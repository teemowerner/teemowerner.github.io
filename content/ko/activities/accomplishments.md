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
  - date_end: ''
    date_start: '2024-05-01'
    description: 'https://m.news.nate.com/view/20240707n09100
보도자료

전국 출산율 데이터, 급여, 시군구 지원 장려금, 교육 예산 등 23 개의 데이터, 200여 개 시군구로 데이터 전처리 후 모델링에 사용.

이후 출산율에 영향을 미치는 상관관계가 큰 변수 를 도출

비지도 학습(K-means 알고리즘을 사용)으로 전주시와 여건이 비슷한 시군구를 분류, 비슷한 시군구의 정책적인 요소 중 전주시보다 출산율이 우수한 시도와 정책을 비교 후 전주시에 정책 개선을 제안'
    organization: 전북특별자치도
    organization_url: https://www.edx.org
    title: 전북보건데이터 경진대회 금상
    url: https://m.news.nate.com/view/20240707n09100
  - certificate_url: https://www.datacamp.com
    date_end: '2024-06-25'
    date_start: '2024-05-01'
    description: ''
    organization: DataCamp
    organization_url: https://www.datacamp.com
    title: 'Object-Oriented Programming in R'
    url: ''

design:
  columns: '1'
---
