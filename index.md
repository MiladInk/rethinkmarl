---
layout: page
title: Rethinking Multi Agent Reinforcement Learning in the Era of Agentic Large Language Models
subtitle: ""
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  (Submitted to ICLR, 2025)
</div>



<div class="sharethis-inline-share-buttons"></div>
<!-- <meta name="thumbnail" content="./img/neurips-logo-new.jpg" /> -->

<!-- <p style="text-align:center;">
  <h2 style="color:red;"><b>Note: Deadline has been extended to September 25, 2024!</b></h2>
</p> -->

**Note that this is a website made for workshop proposal and the workshop is yet to be accepted to ICLR to be organized**

# Workshop Summary

The "Rethinking MARL in the Era of Agentic LLMs" workshop will explore the latest advancements in multi-agent reinforcement learning (MARL) and the role of large language models (LLMs) in these systems. With the rapid development of LLMs, which are evolving from passive language processors to agents capable of complex reasoning and interaction, we are faced with both new opportunities and challenges in multi-agent systems.

LLMs can represent users in complex multi-agent scenarios, collaborating or negotiating with other agents to perform tasks like scheduling meetings or resolving conflicts. This workshop will address how integrating agentic LLMs into multi-agent systems requires new approaches to coordination, communication, safety, and learning dynamics. We will explore these interactions beyond LLMs, extending to all forms of learning agents in multi-agent environments. The workshop aims to inspire innovations in multi-agent reinforcement learning methods for agentic LLMs and sequential decision-making.

By bringing together researchers and practitioners at ICLR 2025, this workshop will focus on key topics such as interacting LLMs, opponent shaping, integrating safety protocols in multi-agent systems, and more. For example, a central question in the field is whether LLMs are necessary for improving performance in MARL or whether tabula rasa learning remains sufficient, and in which scenarios LLMs offer the most benefits. As agents in multi-agent environments become increasingly capable, it is crucial to deepen our understanding of their interactions and ensure safe, efficient operations in complex scenarios.

# Topics of Interest

The workshop will cover a wide range of topics relevant to interacting learning agents, including but not limited to:

- **Interacting LLMs**: Leveraging the power of large language models to enhance communication and decision-making in multi-agent environments.
- **Safety in Multi-Agent Interactions**: Ensuring safety protocols are adhered to in agent-agent and agent-human interactions to avoid unintended consequences.
- **Multi-Agent Systems**: Advancements in the design and optimization of systems involving multiple learning agents, such as deep MARL algorithms.
- **Coordination and Cooperation**: Exploring strategies and algorithms to facilitate effective coordination and cooperation among agents.
- **Debate and Persuasion**: Mechanisms for enabling agents to engage in structured debates and persuasion to resolve conflicts and reach consensus.
- **Opponent Shaping**: Techniques to understand, predict, and influence the behavior and learning dynamics of other agents.

# Key Questions

The workshop will address several key questions through discussions and expert panels, including:

- How can we develop LLM systems that excel in multi-agentic interactions?
- What role can LLMs play in enhancing the learning dynamics of multi-agentic systems?
- How can safety be ensured in interactions between multiple agents?
- What design principles encourage robust, scalable cooperation in multi-agent systems?
- How can opponent shaping and learning awareness be integrated effectively in multi-agent contexts?
- How can debate and persuasion techniques be applied among learning agents to resolve conflicts?

# Other Goals

The primary goal of this workshop is to bring together researchers from academia and industry to share insights, present research findings, and discuss the latest developments in multi-agent systems. Key objectives include:

- Advancing the understanding of how learning agents interact and learn from each other in multi-agent environments.
- Promoting the development of new algorithms and frameworks for agent coordination and cooperation.
- Emphasizing the importance of safety and ethical considerations in multi-agent interactions.
- Showcasing the potential of LLMs to enhance the capabilities of multi-agent systems.

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
