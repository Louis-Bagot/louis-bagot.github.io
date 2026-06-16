---
title: "Deep Learning of Intrinsically Motivated Options in the Arcade Learning Environment"
collection: publications
category: conferences
permalink: /publication/2022-10_deep_explore_options
excerpt: 'We extend Explore Options for Deep Reinforcement Learning, adapting the algorithms for neural-network-based function approximation through the off-policy training of multi-headed neural networks. We provide a clear framework on the different choices of combination of intrinsic and extrinsic rewards. We evaluate the methods on challenging Atari exploration games.'
date: 2022-10-01
venue: 'Deep Reinforcement Learning Workshop NeurIPS 2022'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://openreview.net/forum?id=fFKehNqPxk'
#citation: ''
---

# Abstract
In Reinforcement Learning, Intrinsic Motivation motivates directed behaviors through a wide range of reward-generating methods. Depending on the task and environment, these rewards can be useful, might complement each other, but can also break down entirely, as seen with the noisy TV problem for curiosity. We therefore argue that scalability and robustness, among others, are key desirable properties of a method to incorporate intrinsic rewards, which a simple weighted sum of reward lacks. In a tabular setting, Explore Options let the agent call an intrinsically motivated policy in order to learn from its trajectories. We introduce Deep Explore Options, revising Explore Options within the Deep Reinforcement Learning paradigm to tackle complex visual problems. Deep Explore Options can naturally learn from several unrelated intrinsic rewards, ignore harmful intrinsic rewards, learn to balance exploration, but also isolate exploitative and exploratory behaviors for independent usage. 
We test Deep Explore Options on hard and easy exploration games of the Atari Suite, following a benchmarking study to ensure fairness. Our empirical results show that they achieve similar results than weighted sum baselines, while maintaining their key properties.