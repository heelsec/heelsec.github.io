---
title: People
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}People
{% include section.html %}

{% include list.html data="members" component="portrait" filter="group != 'alumni' && role == 'faculty'" %}
{% include list.html data="members" component="portrait" filter="group != 'alumni' && role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="group != 'alumni' && role == 'masters'" %}
{% include list.html data="members" component="portrait" filter="group != 'alumni' && role == 'undergrad'" %}

{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni
{% include list.html data="members" component="portrait" filter="group == 'alumni'" %}

