---
layout: page
title: Interacting Learning LLM Agents
subtitle: ""
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  (Submitted to ICML, 2025)
</div>



<div class="sharethis-inline-share-buttons"></div>
<!-- <meta name="thumbnail" content="./img/neurips-logo-new.jpg" /> -->

<!-- <p style="text-align:center;">
  <h2 style="color:red;"><b>Note: Deadline has been extended to September 25, 2024!</b></h2>
</p> -->

**Note that this is a website made for workshop proposal and the workshop is yet to be accepted to ICLR to be organized**

# Workshop Summary

The fast progress in Large Language Models (LLMs) is changing how we think about Multi-Agent Reinforcement Learning (MARL). LLMs are no longer just language processors—they are becoming agents that can reason and interact in complex ways. This opens up new opportunities but also brings challenges in multi-agent systems. These agents will work with humans and other learning agents in a wide range of situations. For example, LLMs could act on behalf of users, negotiate with other LLMs, schedule meetings, resolve conflicts, or help with decision-making.

However, the Multi-Agent Reinforcement Learning (MARL) literature shows that current algorithms struggle with social dilemmas, often converging to Nash equilibria (NEs) with low social welfare, even when NEs with significantly higher social welfare exist. This suggests that both our understanding and algorithms for multi-agent interactions are still in their early stages. By exploring how LLMs function in multi-agent environments, we hope to find better ways to handle coordination, communication, safety, and learning among agents—not just LLMs, but all types of learning agents. This workshop focuses on improving multi-agent reinforcement learning methods for LLM-based agents and decision-making in multi-agent systems.

# Topics of Interest

This workshop focuses on interacting LLM agents, exploring topics such as:

- **Coordination and Cooperation**: Strategies to enhance collaboration among LLMs and other learning agents.
- **Structured Debate for Conflict Resolution**: Mechanisms that allow LLMs to engage in structured discussions to resolve conflicts.
- **Multi-LLM and Multi-Human Interactions**: Studying how LLMs interact with each other and with humans in complex environments.
- **Opponent Shaping**: Predicting and influencing the behavior of other agents in multi-agent learning settings.
- **Rethinking MARL Algorithms**: Developing new algorithms to accommodate the dynamics introduced by LLMs.
- **Fundamental Multi-Agent Learning Research**: Exploring theoretical and applied research that advances the understanding of multi-agent systems beyond LLM-based approaches.

# Why is it Appealing to ICML?

As AI improves, agents in multi-agent environments will become more capable, and their interactions will get more complex. Now is a key time to better understand how these agents work together and learn from each other. This workshop is a space for collaboration, helping to develop ideas that will guide the future of MARL as AI continues to advance. ICML, as a major AI/ML conference with a strong focus on reinforcement learning, is the ideal venue for this.

# Past Workshops

Several past workshops have explored key aspects of multi-agent learning:

- **Gamification and Multiagent Solutions (ICLR 2022)**: Examined gamification techniques and game theory for optimizing multi-agent interactions.
- **CoCo MARL (RLC 2024)**: Focused on cooperative and competitive MARL, highlighting communication and coordination.
- **Cooperative Multi-Agent Systems Decision-making and Learning (AAAI 2024)**: Addressed challenges in decision-making and learning for cooperative agents.
- **Open-World Agents (NeurIPS 2024)**: Discussed building adaptive and scalable agents for open-world environments.
- **Training Agents with Foundation Models (RLC 2024)**: Explored how foundation models, such as LLMs, enhance agent communication and decision-making.



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
