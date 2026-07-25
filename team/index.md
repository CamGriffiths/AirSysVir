---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Exploring the unknown is a daunting task. The Airway Systems Virology Lab strives to work at the edge of human knowledge. With a mentality that focuses on using the best technique to answer our questions of interest, the lab is constantly learning. We welcome members with both computational and biology backgrounds. Come join our growing team!

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html %}

<!--## Alumni

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}-->
