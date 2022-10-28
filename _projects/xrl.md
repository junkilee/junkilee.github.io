---
layout: page
title: XRL
description: Explainable reinforcement learning by policy comparison
img: assets/img/projects/xrl.jpg
importance: 1
category: brown
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/xrl.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Reinforcement learning (RL) techniques have led to remarkable results in challenging domains such as Atari games, Go, and Starcraft, suggesting that practical applications lie just over the horizon. Before we can trust decisions made by RL policies, however, we need more visibility into how they work. To explain a reinforcement-learning agent, I propose extending the power of counterfactual reasoning to sequential domains by comparing its policy to a baseline policy at a set of automatically identified decision points. My novel method for selecting important decision points considers a large pool of candidate states and decomposes the agent's value into the reward obtained before vs. after visiting that state. A state is considered important if the accumulated reward obtained after switching to the baseline policy is most different from that obtained after continuing its policy. The engine of this computation is a decomposition of occupancy frequencies of an agent’s policy that characterize the whereabouts of an agent before and after the policy change. Structuring the policy evaluation in this way provides a causal account for its outcome. I have demonstrated the approach on a set of standard RL benchmark domains, providing explanations using the decomposed occupancy frequencies.

J. K. Lee (2022), <b>“Explaining Reinforcement Learning Agents by Policy Comparison”</b>, Ph.D. Dissertation, Brown University.

J. K. Lee and M. L. Littman (2022), <b>“Explaining Reinforcement Learning Agents by Policy Comparison”</b>, The 2022 Multi-disciplinary Conference on Reinforcement Learning and Decision Making (RLDM), Providence, RI