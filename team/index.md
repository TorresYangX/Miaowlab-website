---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab brings together a talented group of graduate students and research assistants with strong foundations in Computer Science and Data Science. We are dedicated to advancing the field of machine reasoning, with a shared focus on Large Language Models, AI for Math, and generative models. If you’re interested in joining this dynamic team, please reach out!

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}


{% include section.html background="images/background.jpg" dark=true %}

Our lab brings together a talented group of graduate students and research assistants with strong foundations in Computer Science and Data Science. We are dedicated to advancing the field of machine reasoning, with a shared focus on Large Language Models, AI for Math, and generative models. If you’re interested in joining this dynamic team, please reach out!

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
