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


# {% include icon.html icon="fa-solid fa-users" %}Alumni



{% include section.html %}

{% include list.html data="alumni" component="portrait" %}



