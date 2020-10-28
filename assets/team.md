---
layout: page
title: The Team
permalink: /team/
---

{% if site.team %}

{% for team in site.team %}
## {{ team.name }}

{{ team.text }}

{% for member in team.members %}
- [{% avatar user=member.user size=24 %} {{ member.name }}](https://github.com/{{ member.user }} "@{{ member.user }}")
{% endfor %}

{% endfor %}

{% else %}

## Core Team

_The Jekyll Core Team's responsibility is to ensure the development and
community around the Jekyll ecosystem thrive._

* Ashwin (@ashmaroli)
* Frank (@DirtyF)
* Matt (@mattr-)

## Emeritus Core Team Members

_Emeritus Core Team Members were once members of Jekyll's Core Team._

* Alfred (@alfredxing)
* Nick (@qrush)
* Parker (@parkr)
* Tom (@mojombo)

{% endif %}
