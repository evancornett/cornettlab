---
---


{% include section.html %}

{% capture text %}

The Cornett Lab is a group of researchers at Indiana University School of Medicine in Indianapolis, Indiana. The lab is based in the Department of Biochemistry and Molecular Biology and is associated with the Indiana University Simon Comprehensive Cancer Center (IUSCC), Stark Neuroscience Research Institute (SNRI), and the Indiana University Center for Computational Biology and Bioinformatics (CCBB). 

{%
  include button.html
  link="team"
  text="Meet the Cornett Lab!"
  icon="fa-solid fa-arrow-right"
  flip=true

%}

{% endcapture %}

{%
  include feature.html
  image="images/research.png"
  link="research"
  title="Research"
  text=text
%}

{% capture text %}

We aim to understand how, where, and why lysine methylation regulates cellular processes. Toward this goal, we use in vitro and cellular biochemistry, chemical biology, and proteomics approaches to map lysine methylation signaling networks and study the regulators of lysine methylation.
{%
  include button.html
  link="research"
  text="Read our latest work!"
  icon="fa-solid fa-arrow-right"
  flip=true
 
%}

{% endcapture %}

{%
  include feature.html
  image="images/group.jpg"
  link="team"
  title="Team"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}
Read about what the Cornett Lab has been up to lately!

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
  image="images/news.jpg"
  link="blog"
  title="News"
  text=text
%}
