---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Citation Metrics
- Total Citations: 80
- h-index: 1
- i10-index: 1

## Journal Articles

1. **Yang, C.**, Mai, J., Cao, X., Burberry, A., Cominelli, F., & Zhang, L. (2023). "ggpicrust2: an R package for PICRUSt2 predicted functional profile analysis and visualization." *Bioinformatics*, 39(8). [Citations: 79]

2. Eterovick, P.C., Schmidt, R., Sabino-Pinto, J., **Yang, C.**, Künzel, S., & Ruthsatz, K. (2024). "The microbiome at the interface between environmental stress and animal health: an example from the most threatened vertebrate group." *Proceedings of the Royal Society B*, 291(2031), 20240917. [Citations: 1]

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
