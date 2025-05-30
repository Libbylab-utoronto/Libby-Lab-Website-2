---
title: Team
nav:
  order: 3
  tooltip: About our team
header: images/banners-01.png
footer: images/banners-02.png
header-dark: true
footer-dark: true
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet our growing team:

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/donnelly_center2.jpg" dark=false %}

Do you want to know more?

{% include section.html %}

Please [reach out]({{ '/recruitment' | relative_url }}) if you are interested in joining! We are happy to chat about possible projects and fellowships. 

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
