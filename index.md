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

# Overview

The Interacting Learning Agents workshop aims to bring together researchers and practitioners to explore the latest developments and open questions in multi-agent systems. It will focus on opponent shaping, learning awareness, and integrating safety protocols in multi-agent interactions.

Recent work has shown the potential of multi-agent learning to enable continuous learning and adaptation of autonomous agents in non-stationary, sequential decision-making problems. Successful application domains include strategic games like Diplomacy and Stratego, as well as real-world settings such as self-driving and AI assistants. With the advancements in artificial intelligence and the availability of large language models (LLMs), agents in multi-agent environments have expanded capabilities, such as the ability to interact through language and access human data. This increased complexity requires a deeper understanding of agent interactions, learning processes, and protocols to guarantee safety in their operations.
Key topics to be discussed include:
- **Coordination and Cooperation**: Mechanisms to facilitate cooperation and coordination in general-sum games between agents to achieve common goals efficiently. What are the advancements and challenges in games and real-world settings that involve coordination?  
- **Opponent Shaping**: Techniques for agents to influence and adapt to their opponent's strategies, enhancing competitive interactions. 
- **Multi-agent Agentic LLMs**: Tentative research questions: What are the main bottlenecks in integrating LLMs in multi-agent settings? 
Debate and Persuasion: Exploring how agents can engage in structured debates and persuasive dialogues to resolve conflicts and reach consensus. How can LLMs facilitate coordination in general-sum games? 
- **Decision-making with a mixture of experts**: Exploring how contradicting preferences can be aggregated and how human and agent suggestions should be weighted. 
- **Tentative research questions**: What metrics can quantify the importance of suggestions? 
- **Evaluation and Safety in Multi-agent Systems**: Addressing the critical aspect of safety in multi-agent systems, ensuring robust and secure operations in dynamic environments.
The workshop will feature keynote presentations, panel discussions, and interactive sessions to foster collaboration and knowledge exchange among participants. By immersing into these diverse yet interconnected topics, the "Interacting Learning Agents" workshop aims to push the boundaries of multi-agent research and pave the way for more sophisticated, cooperative, and safe AI systems.
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
