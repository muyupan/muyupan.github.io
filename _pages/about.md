---
permalink: /

author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi, this is Muyu Pan. I am an undergraduate student at The Pennsylvania State University, **Schreyer Honors College**, pursuing a B.S. in Computer Science with a minor in Mathematics. I have the privilege of conducting research under the mentorship of [Prof. Rui Zhang](https://ryanzhumich.github.io/) and [Prof. Mahfuza Farooque](https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=WlyWLHMAAAAJ&sortby=pubdate).

My research interest covers **AI Safety** (Hallucination Detection and Mitigation) and **Applied AI** (LLMs for decision making, Robotic Learning, and AI for Engineering). I am currently working on utilizing model internal signals to mitigate model hallucination through GRPO RL. I aim to pursue **Safe and Robust Machine Learning** frameworks to bridge the gap between academic innovation and real-world utility in the long run. I am always happy to chat and discuss potential collaborations. Feel free to contact me via email at mfp5696 AT psu.edu.

<h2 id="publications">Publications</h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2 id="projects">Projects</h2>
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}