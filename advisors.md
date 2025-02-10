---
layout: page
title: Rethinking Multi Agent Reinforcement Learning in the Era of Agentic Large Language Models
subtitle: ""
use-site-title: true
---

# Advisors
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  {% for p in site.data.advisors %}
  {% if forloop.index<15 %}
  <div class="row">
    <div class="col-sm">
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    </div>
    <div class="col">
    {% capture id %}{{ p[1] }}{% endcapture %}
    {% include profile_detail.html p=p %}
    </div>
  </div>
  <br>
  {% endif %}
  {% endfor %}
</div>
‍