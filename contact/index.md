---
title: Contact us
nav:
  order: 5
  tooltip: mail, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our assistant is here to help you with common questions about our service and sales. For technical support, please email us at support_info_deltaG@gmail.com.

{%
  include button.html
  type="email"
  text="duynth29@gmail.com"
  link="duynth29@gmail.com"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/office.jpg"
  caption="Office visit"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/assistance.jpg"
  caption="Need help?"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
