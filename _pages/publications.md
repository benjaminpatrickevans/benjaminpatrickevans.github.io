---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Some of my publications are included below. For most recent list, please visit my [Google Scholar page](https://scholar.google.com/citations?user=yfrOml0AAAAJ&hl=en&oi=ao). Generally, I try and make all my research open access, either via releasing a Preprint, providing source code, or using open-access journals when possible. If any research is not available, feel free to contact me directly and I will be happy to provide a copy or source code.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
