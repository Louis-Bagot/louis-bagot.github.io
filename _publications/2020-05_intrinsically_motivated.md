---
title: "Learning intrinsically motivated options to stimulate policy exploration"
collection: publications
category: conferences
permalink: /publication/2020-05_intrinsically_motivated
excerpt: 'We study intrinsic motivation for exploration in RL and propose an aternative to the wide-spread approach of a weighted sum of rewards. We show that decoupling exploration and exploitation through different agents enables to scale to multiple intrinsic rewards, ignore harmful signals and improve task transfer. We propose to switch between agents through an Explore Option (an additional to call the Explorer agent), leading to exploration-focused Hierarchical RL.'
date: 2020-05-01
venue: '4th Lifelong Machine Learning Workshop at ICML 2020'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://openreview.net/forum?id=Vcf1fDmBYJk'
#citation: ''
---

# Abstract
A Reinforcement Learning (RL) agent needs to find an optimal sequence of actions in order to maximize rewards. This requires consistent exploration of states and action sequences to ensure the policy found is optimal.
One way to motivate exploration is through intrinsic rewards, i.e. agent-induced rewards to guide itself towards interesting behaviors.
We propose to learn from such intrinsic rewards through exploration options, i.e. additional temporally-extended actions to call separate policies (or "Explorer" agents) associated to an intrinsic reward. We show that this method has several key advantages over the usual method of weighted sum of rewards, mainly task-transfer abilities and scalability to multiple reward functions.

