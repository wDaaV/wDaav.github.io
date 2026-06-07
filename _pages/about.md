---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello there. I'm Davide, a B.Sc. graduate in Computer and Automation Engineering. I'm a 23-year-old computer, music and motor enthusiast, looking for innovations and experiences.


### Formazione

| Periodo | Titolo | Istituzione |
|---------|--------|-------------|
| 2020–2024 | Dottorato in Informatica | Università di  |
| 2018–2020 | Laurea Magistrale in Informatica | Università di  |
| 2016–2021 | Laurea Triennale in Informatica | Università di  |


## Progetti

{% assign progetti = site.projects | sort: 'date' | reverse %}
{% for progetto in progetti %}

### [{{ progetto.title }}]({{ progetto.url | relative_url }})

{{ progetto.excerpt | strip_html }}

{% if progetto.link %}[🔗 Vai al progetto]({{ progetto.link }}){:target="_blank"}{% endif %}

---
{% endfor %}

## CV

