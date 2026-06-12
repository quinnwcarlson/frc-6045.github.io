---
title: Documented Problems
layout: guide
permalink: /documentedproblems.html
---

<p>We have experienced these problems with our robot and struggled to fix them, so we are writing them here for future reference and in case they are useful for other teams.</p>

{% for p in site.problems %}
<details>
  <summary>{{ p.title }}</summary>
  <div>{{ p.content }}</div>
</details>
{% endfor %}
