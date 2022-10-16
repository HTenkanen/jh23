---
title: "J & H"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/kuu.jpg
excerpt: "27.5.2023 - Suomenlinna, Helsinki"
intro: 
  - excerpt: 'Lämpimästi tervetuloa hääjuhlaamme Suomenlinnaan.'
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    title: "Ilmoittautuminen"
    excerpt: "Ilmoittauduthan hääjuhlaamme 15.4.2023 mennessä."
    url: "ilmoittaudu"
    btn_label: "Ilmoittaudu täältä"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    title: "Hääinfo"
    excerpt: "Täältä löydät lisäinfoa hääjuhlastamme."
    url: "info"
    btn_label: "Lue lisää"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Saapuminen"
    excerpt: "Täältä löydät käytännön ohjeita kuinka saapua juhlaamme."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
