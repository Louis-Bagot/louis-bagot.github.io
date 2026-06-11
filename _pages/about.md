---
permalink: /
title: "Louis Bagot -- Academic website"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a Temporary Assistant Professor-Researcher (ATER) at Université Lyon 1 in France, researching within laboratory LIRIS within the SyCoSMA team and teaching in the Informatics department. 

This 2026-2027 academic year I am responsible for the Machine Learning course in the Artificial Intelligence Master of the Informatics department of Université Lyon 1, "*Techniques d'Apprentissage Automatique*". If you are looking for information about this course, please check out the dedicated [Teaching page](teaching.html). 

I am an engineer in Applied Mathematics from INSA Rouen and I completed my Ph.D in Computer Science at the University of Antwerp in Belgium, within laboratories IDLab and imec.

# Research Interests

My main research interest is **Reinforcement Learning** (RL), where an *agent* interacts in an *environment* and needs to maximize *reward* through trial-and-error.
I aim to train general agent which can adapt to any task and problem, which I tackle through the self-supervised learning of general skills and representations. 
My fields of study are the following:

- **Task Transfer and Zero-Shot RL** centers around the learning of *Behavioral Foundation Models*: models that can produce optimal policies for any task, while training without rewards. I am interested in the theoretical foundations of skills and representations, the training of the models, their usage and transfer potential, their interpretability, and their composition through Hierarchical RL and planning.

- **Exploration and Intrinsic Motivation** studies the learning of behaviors and representations which can help quickly explore the environment, its interactions and rewards. Intrinsic motivation proposes to generate artificial rewards to motivate the agent beyond what is explicitly specified by the task. Intrinsic Motivation and zero-shot RL are deeply tied: most methods of one field can be seen through the prism of the other. 

- **Hierarchical Reinforcement Learning** (HRL) proposes to adopt a "divide and conquer" strategy by decomposing the full control problem into a bunch of simpler sub-problems, generally tackled in practice with policies which can call other policies (*options*). The skills learned through intrinsic motivation and zero-shot RL are natural candidates for HRL, and I am interested in building multi-layered task hierarchies from reward-free training.

- **Continual Reinforcement Learning** (CRL) considers the full lifetime of the agent and aims for *Lifelong Learning*, or how to gradually amass knowledge about the world and quickly adapt to new situations in an unending cycle. The task transfer scenario of zero-shot RL is a specific setup for CRL, and I am interested in extending this relationship: gradually and actively building the set of skills and representations as a basis of knowledge through *curriculum learning* (harder and harder tasks), but also facilitating the usage and adaptation of this knowledge during transfer.

- **Model-Based Reinforcement Learning** (MBRL) learns an explicit model of the environment, in other words, predicting the consequences of our actions (sometimes called *World Models*). I am particularly interested in *Planning*, i.e., predicting the consequences of our actions to plan optimal sequences, especially in the context of Hierarchical RL with policy-scale modeling and planning.

- **Deep Learning** is the basis of current state-of-the-art through the training of deep neural networks as function approximators; from that perspective most of my research is *Deep Reinforcement Learning*.

# Teaching
At the Master level I mainly teach the foundations of Artificial Intelligence, in particular through data and learning: Data Science, Machine Learning, Deep Learning and Reinforcement Learning. 

At the License level I teach most of the foundations of Computer Science: programming and algorithms, data structures, web and networking. I would be very interested in teaching the more theoretical aspects of scientific calculation and applied mathematics: linear algebra, optimization, simulation, probabilities and statistics.

Check out the [Teaching page](teaching.html) for courses I currently teach, and my [CV page](cv.md) for an overview of all my teaching experience.

# Academic training
See the [CV page](cv.md) for a more in-depth detail of my academic background.

### Ph.D in Reinforcement Learning
I completed my PhD at the University of Antwerp from 2020 to 2024 at IDLab under the supervision of Kevin Mets and Steven Latré. My thesis is titled "*Transfer and Zero-shot Reinforcement Learning: Learning Behaviors Without a Reward Function*" and centers around the learning of general skills and representations. It can be broadly broken down into two parts:

- **Exploration and Intrinsic Motivation**: I studied the usage of intrinsic rewards for exploration, mainly focusing on finding alternatives to a weighted sum of rewards, which I proposed to do via Hierarchical RL.

- **Task Transfer**: generating a family of intrinsic rewards naturally leads to a wide range of skills which can be used to solve downstream tasks, which became my next research direction. I studied how we can train and foster these skills to quickly generate optimal policies, which I mainly tackled using Successor Features.

### Engineer in Applied Mathematics
I completed my training as an engineer at INSA Rouen from 2014 to 2019, with a specialty in Applied Mathematics. I studied a semester at Bishop's University in Sherbrooke, Canada, to learn Machine Learning. 
I realized my engineering internship as a research engineer at EDF, where I studied the optimization of the layout of a nuclear power plant through Deep Evolutionary Algorithms. 