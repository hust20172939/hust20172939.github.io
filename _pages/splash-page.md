---
title: "DucAnh's Blog"
layout: splash
permalink: / #/splash-page/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#fff"
  overlay_filter: "0.5"
  overlay_image: /assets/image/header.jpg
  actions:
    - label: "Learn More"
      url: "/"
  caption: #"Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Đây là nơi để mọi người có thể tìm hiểu thêm về cuộc sống tẻ nhạt của Đức Anh"

intro: 
  - excerpt: #"Đây là nơi để mọi người có thể tìm hiểu thêm về cuộc sống tẻ nhạt của ĐAnh"
feature_row:
  - image_path: assets/image/technology.jpg 
    image_caption:  #"Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 1"
    title: "Technology" 
    url: /categories/technology/
    excerpt: "Một vài công nghệ cơ bản mà Đức Anh học được ở trường" #"This is some sample content that goes here with **Markdown** formatting."
    btn_label: "Read More"
    btn_class: "btn--primary"

  - title: "Travel" #(/categories/travel/) #"Placeholder 2"
    image_path: assets/image/travel.jpg 
    alt: "Travel" #(/categories/travel/) #"placeholder image 2"
    excerpt: "Nơi lưu trữ ảnh và những bài review về những vùng đất Đức Anh đã đi qua" #"This is some sample content that goes here with **Markdown** formatting."
    url: /categories/travel/
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/image/dailylife.jpg
    title: "Opinion" #(/categories/opinion/)
    excerpt: "Quan điểm, suy nghĩ của Đức Anh về những vấn đề trong cuộc sống" #"This is some sample content that goes here with **Markdown** formatting."
    url: /categories/opinion/
    btn_label: "Read More"
    btn_class: "btn--primary"

# feature_row2:
#   - image_path: assets/image/rem.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Left Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row3:
#   - image_path: assets/image/rem.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Right Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row4:
#   - image_path: assets/image/rem.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Center Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

<!-- {% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %} -->