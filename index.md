---
header-dark: false
footer-dark: false
---
# **Revolutionizing Antibody-Antigen Discovery and Characterization by Generative AI**

{% include figure.html image="images/technology/antigen_antibody_website.gif" caption="" width="50%"%}
<!--
Accessibility: The figure.html include supports alt text and captions for screen readers. Setting style="width:50%;" ensures the image is scaled to 50% width, which can improve readability and layout for users, including those with visual or cognitive disabilities who benefit from less cluttered pages.
-->
<!--
Accessibility: The image is inserted using the figure.html include, which supports captions and alt text for screen readers, improving accessibility for visually impaired users.
-->

{% include section.html %}

## Highlights

{% capture text %}

We are improving healthcare for cancer patients by harnessing the power of protein language models to identify mutations that impact therapy decisions—delivering faster, more cost-effective solutions.

{%
  include button.html
  link="technology"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="technology"
  title="Our Technology"
  text=text
%}

{% capture text %}

Our technology leverages advanced protein language models to identify mutations that can affect treatments in cancer patients. 

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
  image="images/photo.jpg"
  link="pipelines"
  title="Our Pipelines"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our pipeline involves data preprocessing, mutation mapping, model inference to predict mutation impact, and result interpretation, providing actionable insights for personalized cancer treatment.

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
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
