---
title: Contact
nav:
  order: 8
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

You can find us at the [Donnelly Center for Cellular + Biomolecular Research](https://thedonnellycentre.utoronto.ca/) at the [University of Toronto](https://www.utoronto.ca/).

{%
  include button.html
  type="email"
  text="email"
  link="ashley.libby@crick.ac.uk"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/wt5cezwJ6Bjffg7P6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/website_logos-03.jpg"
  caption="University of Toronto"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/website_logos-04.jpg"
  caption="Donnelly within UofT"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

