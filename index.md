---
---

# Cornett Lab @ IUSM



{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Research.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We aim to understand how, where, and why lysine methylation regulates cellular processes. Toward this goal, we use in vitro and cellular biochemistry, chemical biology, and proteomics approaches to map lysine methylation signaling networks and study the regulators of lysine methylation.

{%
  include button.html
  link="Lab Members"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/group.jpg"
  link="team"
  title="Lab Members"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="blog"
  text="Latest news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/highlight.jpg"
  link="blog"
  title="News"
  text=text
%}
