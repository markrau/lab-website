---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team is great!

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator' and alumni != true" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and alumni != true" %}

{% include section.html %}

## Previous Members

{% include list.html data="members" component="portrait" filter="alumni == true" %}

{% include section.html background="images/background.jpg" dark=true %}

These will be some pictures of us doing fun things...

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
