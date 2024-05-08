---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are a dynamic research team from the Hong Kong University of Science and Technology. If you are interested in our research directions or have any questions about our research achievements, please feel free to contact us.

{%
  include button.html
  type="email"
  text="maolinwang@ust.hk"
  link="maolinwang@ust.hk"
%}

{%
  include button.html
  type="email"
  text="dongz@ust.hk"
  link="dongz@ust.hk"
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
  image="images/hkust1.jpg"
  caption="Entrance Piazza"
%}
{% endcapture %}

{% capture col2 %}
{%
  include figure.html
  image="images/hkust2.jpg"
  caption="Campus Panorama"
%}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}