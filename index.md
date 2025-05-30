---
layout: page
title: Rethinking Multi-Agent Reinforcement Learning in the Age of Interacting LLMs
subtitle: ""
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  (Submitted to Neurips, 2025)
</div>



<div class="sharethis-inline-share-buttons"></div>
<!-- <meta name="thumbnail" content="./img/neurips-logo-new.jpg" /> -->

<!-- <p style="text-align:center;">
  <h2 style="color:red;"><b>Note: Deadline has been extended to September 25, 2024!</b></h2>
</p> -->

**Note that this is a website made for workshop proposal and the workshop is yet to be accepted to NeurIPS 2025 to be organized**

**Workshop Summary**

Large Language Models (LLMs) are no longer just text generators. They are becoming agents that can reason, negotiate, and work together. This shift creates new challenges for Multi-Agent Reinforcement Learning (MARL). Today’s MARL methods often struggle in general-sum settings and can settle on low-welfare Nash equilibria even when better solutions exist. By studying LLM agents in multi-agent scenarios, this workshop will explore new ways to improve coordination, communication, conflict resolution, and safety across all agents. We aim to bring together researchers to push MARL forward for LLM-based agents and other multi-agent systems.

**Topics of Interest**

* **Coordination & Cooperation**
  Approaches to build and maintain high-welfare collaboration among LLMs and other agents.

* **Structured Debate & Conflict Resolution**
  Design dialogue and negotiation protocols to settle disagreements effectively.

* **Multi-LLM & Multi-Human Interactions**
  Study how LLM agents and people interact in mixed groups.

* **Opponent Shaping & Modeling**
  Techniques to predict and guide other agents’ learning without sacrificing fairness or robustness.

* **Rethinking MARL Algorithms**
  Develop new MARL methods that leverage the reasoning and communication strengths of LLMs.

* **Fundamental Multi-Agent Learning**
  Theoretical and applied work on general multi-agent problems, beyond just LLMs.

**Why NeurIPS?**

LLM agents are growing more capable, and their interactions are becoming more complex. NeurIPS is the leading venue for reinforcement learning and multi-agent research. It is the ideal place to share new findings, start collaborations, and shape the future of MARL with intelligent language agents.

**Past Workshops**

* **Gamification and Multiagent Solutions (ICLR 2022)**
  Explored game-theory and gamification for multi-agent tasks.

* **CoCo MARL (RLC 2024, 2025)**
  Focused on cooperation, competition, and agent communication.

* **Cooperative Multi-Agent Systems: Decision-Making and Learning (AAAI 2024)**
  Addressed decision-making in cooperative settings.

* **Open-World Agents (NeurIPS 2024)**
  Discussed adaptive agents for open-ended environments.

Despite these efforts, none have centered on the new challenges and opportunities that arise when LLMs act as agents in multi-agent systems. This workshop fills that gap.





<hr>

# Speakers
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
    {% for p in site.data.speakers %}
    {% if forloop.index<=5 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>5 and forloop.index<=10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
<a href="speakers">More Info</a>
</div>

<hr>

# Advisors

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <!-- <br> 
  <div class="row" style="margin: -30px;"> -->
  <div class="row">
    {% for p in site.data.advisors %}
    {% if forloop.index<=4 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.advisors %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>4 and forloop.index<=8%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>

# Organizers
<!-- # Organizers -->

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <!-- <br> 
  <div class="row" style="margin: -30px;"> -->
  <div class="row">
    {% for p in site.data.organizers %}
    {% if forloop.index<=4 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>4 and forloop.index<=8%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>





<!-- # Program Committee
<div class="container">
  <ul class="list-group list-group-flush">
    {% for p in site.data.pc.people %}
      <li class="list-group-item col-xs-6 col-sm-4 col-md-3">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr> -->

<!-- # Related Venues

<div class="container" style="margin-bottom: 10px;"></div>
- [ICML'24 Workshop on AI4MATH - AI for Math Workshop @ ICML 2024](https://sites.google.com/view/ai4mathworkshopicml2024)
- [NeurIPS'23 Workshop on MATH-AI - The 3rd Workshop on Mathematical Reasoning and AI](https://mathai2023.github.io/)
- [NeurIPS'22 Workshop on MATH-AI - Toward Human-Level Mathematical Reasoning](https://mathai2022.github.io/)
- [NeurIPS'21 workshop on MATHAI4ED - Math AI for Education: Bridging the Gap Between Research and Smart Education](https://mathai4ed.github.io/)
- [ICLR'21 workshop on MATH-AI - The Role of Mathematical Reasoning in General Artificial Intelligence](https://mathai-iclr.github.io/)
- [NeurIPS'20 Workshop on KR2ML - Knowledge Representation & Reasoning Meets Machine Learning](https://kr2ml.github.io/2020)
- [NeurIPS'20 workshop on Advances and Opportunities: Machine Learning for Education](https://www.ml4ed.org/)
- [ICML'20 workshop on Bridge  Between Perception and Reasoning: Graph Neural Networks & Beyond](https://logicalreasoninggnn.github.io)

<div class="container" style="margin-bottom: 10px;"></div>

<hr>

Contact: <mathai.neurips2024@gmail.com>. -->
