---
title: Lab Members
nav:
  order: 3
  tooltip: About our members
---

# {% include icon.html icon="fa-solid fa-users" %}Lab Members



{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}


{% include section.html %}

{% capture content %}

{% include figure.html image="images/group2020.png" %}
{% include figure.html image="images/group2022.png" %}
{% include figure.html image="images/group2023.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
