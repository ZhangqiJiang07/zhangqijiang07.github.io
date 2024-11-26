---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About Me
Hi! I am a second-year M.S. student in *Systems Science* at [National University of Defense Technology](https://english.nudt.edu.cn/), advised by Assoc. Prof. [Tingjin Luo](https://horizonailab.github.io/homepage/). Previously, I was an undergraduate student in *Information and Computing Science* at [Shanxi Univeristy](https://www.sxu.edu.cn/).

I work on **improving the reliability and safety of deep learning models**. During my Master’s program, I am interested in learning robust multi-view models against incomplete data and limited supervision information. Currently, I also research hallucinations in vision-language models, working with Assoc. Prof. [Xu Yang](https://yangxuntu.github.io/) from Southeast University.


{% include_relative includes/news.md %}


{% include_relative includes/pub.md %}


# Projects


# Honors and Awards
