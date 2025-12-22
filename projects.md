---
layout: default
title: Projects
permalink: /projects/
---

<h1 class="mt-4">Projects</h1>
{% assign projects = site.projects %}
{% for proj in Projects %}
<div class="projitem">
  <div class="projtitle">{{ proj.title }}</div>
  <div class="projrole">{{ proj.role}}</div>
  <div class="projurl">{{ proj.url}}</div>
</div>
{% endfor %}