---
title: Home
---

# Workshop on Applied Mathematics

{% include figure.html img="Workshop.jpeg" alt="intro image here" width="100%" %}

This is an initiative of the PhD students in Mathematics: Cristhian Núñez, Boris Bermudez, Joaquín Carvajal, and Jhon Rodriguez.

<p style="text-align: justify;">
This workshop aims to bring together researchers and students to share recent advancements and foster the exchange of ideas in key areas such as Optimization, Machine Learning, Numerical Analysis, Inverse Problems, and Discrete Mathematics. By creating a collaborative and interdisciplinary environment, we seek to encourage discussions that bridge different mathematical fields and highlight the far-reaching impact of applied mathematics in science, engineering, and technology. Our goal is to promote meaningful interactions, inspire innovative research, and strengthen the connections between academia and industry. The event will take place on March 6–7, 2025, at the San Joaquín campus of the Pontifical Catholic University of Chile, in the Ninoslav Bralic Auditorium, located within the Faculty of Mathematics
</p>

"Mathematics is the queen of the sciences, and the theory of applications of mathematics is the queen of engineering." – James Clerk Maxwell


<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by [Pontificia Universidad Católica de Chile](http://www.uc.cl/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
