---
permalink: /
redirect_from: 
  - /about/
  - /about.html
title: "About me"
---

<div style="text-align: justify;" markdown="1">

Hello there. I'm Davide, a B.Sc. graduate in Computer and Automation Engineering. I'm a 23-year-old computer, music and motor enthusiast, looking for innovations and experiences.


## Education

- B.Sc. graduate in Computer and Automation Engineering, Polytechnic of Bari.
- Industrial Technical Diploma in Computer Science and Telecommunications, I.I.S.S "E. Majorana" Martina Franca (TA).


## Projects

{% assign progetti = site.projects | sort: 'order' | reverse %}
{% for progetto in progetti %}

### [{{ progetto.title }}]({{ progetto.url | relative_url }})

{{ progetto.excerpt | strip_html }}

{% if progetto.link %}[🔗 Vai al progetto]({{ progetto.link }}){:target="_blank"}{% endif %}

{% endfor %}

## Certifications 

- Introduction to Cybersecurity, provided by Cisco Networking Academy
- MATLAB Onramp, provided by MathWorks

## CV

- [EN]()
- [IT]()

</div>
