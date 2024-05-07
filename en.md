---
title: RagamBahasa
layout: home
description: Grassroot movement initiation of Indonesian Local Language Resources Collecting.
intro_image: "https://cdn.pixabay.com/photo/2021/07/08/14/06/general-soedirman-6396997_960_720.jpg" # "images/illustrations/pointing.svg"
intro_image_absolute: false
intro_image_hide_on_mobile: true
show_call_box: false
lang: en
---

# RagamBahasa
{% for item in site.data.home_hero.i18n  %}
{% if item.language == "en" %}
{{ item.subtitle }}
{% endif %}
{% endfor %}
