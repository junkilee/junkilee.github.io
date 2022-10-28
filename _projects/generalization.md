---
layout: page
title: generalization
description: Measuring and characterizing generalization in deep reinforcement learning
img: assets/img/projects/generalization.jpg
importance: 2
category: brown
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/generalization.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Deep reinforcement learning (RL) methods have achieved remarkable performance on challenging control tasks. Observations of the resulting behavior give the impression that the agent has constructed a generalized representation that supports insightful action decisions. We re-examine what is meant by generalization in RL, and propose several definitions based on an agent's performance in on-policy, off-policy, and unreachable states. We propose a set of practical methods for evaluating agents with these definitions of generalization. We demonstrate these techniques on a common benchmark task for deep RL, and we show that the learned networks make poor decisions for states that differ only slightly from on-policy states, even though those states are notselected adversarially. We focus our analyses on the deep Q-networks (DQNs) that kicked off the modern era of deep RL. Taken together, these results call into question the extent to which DQNs learn generalized representations, and suggest that more experimentation and analysisis necessary before claims of representation learning can be supported.


Sam Witty, Jun Ki Lee, Emma Tosch, and Akanksha Atrey, Kaleigh Clary, Michael L Littman, David Jensen (2021), <b>"Measuring and characterizing generalization in deep reinforcement learning"</b>, Applied AI Letters

S. Witty, J. K. Lee, E. Tosch, A. Atrey, M. L. Littman, and D. Jensen (2018), <b>“Measuring and Characterizing
Generalization in Deep Reinforcement Learning,”</b> on Arxiv preprint, arXiv:1812.02868

S. Witty, J. K. Lee, E. Tosch, A. Atrey, M. L. Littman, and D. Jensen (2018), <b>“Measuring and Characterizing
Generalization in Deep Reinforcement Learning,”</b> in NeurIPS 2018 Workshop, Critiquing and Correcting
Trends in Machine Learning. 