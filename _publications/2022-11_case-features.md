---
title: "A Case for Representation-Based Successor Features for Transfer in Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2022-11_case-features
excerpt: 'Useless?'
date: 2022-10-01
venue: 'BNAIC/BeNeLearn 2022'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://bnaic2022.uantwerpen.be/wp-content/uploads/BNAICBeNeLearn_2022_submission_8036.pdf'
#citation: ''
---

# Abstract
Successor Features stand at the boundary between model-free and model-based Reinforcement Learning. By predicting a sum of features instead of a sum of rewards, they enable very efficient transfer learning through the General Policy Improvement Theorem. Recent work has shifted the focus of the feature space from learned features to a well-chosen set of base rewards. While this framework greatly improves stability, it discards the flexibility to generalize outside the base reward space. In this paper, we aim to rekindle interest in" representation-based" Successor Features for transfer learning, by clarifying the possible design choices and providing simple cases where they prevail. In a robot arm scenario, we find that they more easily transfer to unseen tasks without suffering from instabilities during training. We provide visual interpretation of the learnt features to explain this performance.