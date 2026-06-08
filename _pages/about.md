---
permalink: /
redirect_from: 
  - /about/
  - /about.html
---

# About me

Hello there. I'm Davide, a B.Sc. graduate in Computer and Automation Engineering. I'm a 23-year-old computer, music and motor enthusiast, looking for innovations and experiences.


## Education

- Industrial Technical Diploma in Computer Science and Telecommunications, I.I.S.S "E. Majorana" Martina Franca (TA).
- B.Sc. graduate in Computer and Automation Engineering, Polytechnic of Bari.


## Projects

{% assign progetti = site.projects | sort: 'date' | reverse %}
{% for progetto in progetti %}

### [{{ progetto.title }}]({{ progetto.url | relative_url }})

{{ progetto.excerpt | strip_html }}

{% if progetto.link %}[🔗 Vai al progetto]({{ progetto.link }}){:target="_blank"}{% endif %}

{% endfor %}

## Certifications 

- Introduction to Cybersecurity, provided by Cisco Networking Academy
- MATLAB Onramp, provided by MathWorks

## CV

- EN
- IT
