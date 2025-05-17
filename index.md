---
header-dark: false
footer-dark: false
---
# **Revolutionizing Antibody-Antigen Discovery and Characterization by Generative AI**

<!-- {% assign slider_images = site.data.slider_images | default: array %}
{% if slider_images.size == 0 %}
  {% assign slider_images = array %}
  {% assign slider_images = slider_images | push: "images/technology/EGFR-02.png" %}
{% endif %}

{% include slider.html 
  images=slider_images
  width="50%"
  height="auto"
  autoplay=true
  interval=10000
%} -->

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="technology"
  text="Learn more about our technology"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/technology/EGFR-02.png"
  link="technology"
  title="Our Technology"
  text=text
%}

{% capture text %}
pipline captions here 
{%
  include button.html
  link="pipelines"
  text="Browse our pipelines"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/technology/EGFR-01.png"
  link="pipelines"
  title="Our Pipelines"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}



{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/TEAM.png"
  link="team"
  title="Our Team"
  text=text
%}
