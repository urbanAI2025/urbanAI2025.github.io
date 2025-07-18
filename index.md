---
title: Home
---

# UrbanAI: Harnessing Artificial Intelligence for Smart Cities

{% include figure.html img="urbanai.png" alt="intro image here" caption="Library workshop" width="75%" %}

As the world population becomes increasingly urban, incredible innovation is required to sustain
such dense populations in a safe and healthy manner. Urban areas are responsible for over 70% of
global carbon emissions and energy consumption, driven by infrastructure and transportation
systems that often remain inefficient or outdated despite advances in technology. AI and machine learning present immense opportunities to reshape urban environments, optimizing everything
from energy use and transportation networks to public health and governance, addressing urgent
challenges in areas as diverse as building optimization and sustainability, pollution mitigation,
infrastructure maintenance, urban planning, traffic management, and civic life. However, applying AI solutions to these challenges is not easy. Engineers must deal with a wide range of
obstacles, including complex and non standardized management systems, diverse and non-integrated
data sources, security and privacy risks, and continuous integration and maintenance. This workshop aims to engage the machine learning community in addressing urban optimization challenges,
overcoming real world obstacles that prevent adoption of solutions, and fostering interdisciplinary
collaboration among experts in infrastructure, transportation, and public health. By leveraging
cutting-edge ML methodologies, participants can develop scalable solutions to enhance efficiency,
sustainability, and quality of life in urban areas. Confirmed speakers from fields including power
systems, building optimization, transportation, water, energy systems, climate science, and building
control, will lead discussions on establishing benchmarks, developing robust methodologies, and
creating solutions with measurable real-world impact. This workshop offers the ML community
a unique platform to directly contribute to sustainable and intelligent urban development, helping
cities globally meet climate goals, improve public services, and enhance overall urban resilience. Unlike existing ML-focused workshops on climate and physical systems, UrbanAI explicitly
addresses the multifaceted challenges of urban environments, bringing international experts together
for the first time at a major ML conference

*See also:* [workshop-template-b](https://evanwill.github.io/workshop-template-b/), Bootstrap version.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by [University of Idaho Library](http://www.lib.uidaho.edu/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
