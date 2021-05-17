---
title: "Projects"
layout: splash
author_profile: true
permalink: /projects/
date: 2020-04-08
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/splash/coffee.jpeg
intro: 
  - excerpt: '진행중인 프로젝트 목록'


feature_row:
  - image_path: /assets/splash/feat1-1.jpg
    title: "Placeholder 1"
    excerpt: "Sample text 1 with **markdown** formatting."
    url: "/categories/#development"
    btn_label: "Read More"
    btn_class: "btn--primary"



feature_row_left:
  - image_path: /assets/splash/feat1-1.jpg
    title: "Left aligned placeholder 1"
    excerpt: "Left-aligned image centered with"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row_left" type="left" %}

{% include feature_row id="feature_row_center" type="right" %}

{% include feature_row id="feature_row_center" type="center" %}