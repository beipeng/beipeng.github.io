---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

### Investigating How Non-Expert Humans Design Curricula
In this project, we are interested in interactive learning setting where humans could design a curriculum of tasks and study how they design curricula. A better understanding of the curriculum-design strategies used by non-expert humans may help us to 1) understand the general principles that make some curriculum-design strategies better than others, and 2) inspire the design of new machine-learning
algorithms and interfaces that better accommodate the natural tendencies of human trainers.

- <b>Related Papers:</b>
  > <b>Curriculum Design for Machine Learners in Sequential Decision Tasks</b> <br>
<b>Bei Peng</b>, James MacGlashan, Robert Loftin, Michael L. Littman, David L. Roberts, and Matthew E. Taylor. <i>IEEE Transactions on Emerging Topics in Computational Intelligence, 2018. </i>[[pdf]](http://beipeng.github.io/files/2018ieee-tetci-peng.pdf)


### Adapting Agent Action Speed to Improve Task Learning from Humans <b>[[Video]](https://www.youtube.com/watch?v=AJQSGD_XPrk)</b>
In this project, we aim to design a better representation of the learning agent that is able to elicit more natural and effective communication between the human trainer and the learner, while treating human feedback as discrete communication that depends probabilistically on the trainer’s target policy. This is different than most exisitng work on Interactive Reinforcement Learning, where they focus on interpreting and incorporating non-expert human feedback to speed up learning.

- <b>Related Papers:</b>
  > <b>A Need for Speed: Adapting Agent Action Speed to Improve Task Learning from Non-Expert Humans</b> <br>
Bei Peng, James MacGlashan, Robert Loftin, Michael L. Littman, David L. Roberts, and Matthew E. Taylor. <i>In Proceedings of the 2016 International Conference on Autonomous Agents and Multiagent Systems (AAMAS), May 2016. </i>[[pdf]](http://beipeng.github.io/files/2016aamas-peng.pdf)

- <b>In the News:</b>
  > [Sit, Heel, Compute: Computers Learn Better by Imitating Dogs](https://www.livescience.com/54985-training-robots-to-learn-like-dogs.html) [Live Science]

  > [Animal training techniques teach robots new tricks](https://www.sciencedaily.com/releases/2016/05/160516125939.htm) [Science Daily]


### Learning from Discrete Human Feedback
In this project, we consider the problem of a human trainer teaching an agent via providing positive or negative feedback. 
Most existing work on Interactive Reinforcement Learning has treated human feedback as a numerical value that the agent 
seeks to maximize, and has assumed that all trainers will give feedback in the same way when teaching the same behavior. 
In contrast, we treat the feedback as a human-delivered discrete communication between the trainers and the learners and 
different training strategies will be chosen by them. We propose a probabilistic model to classify different training strategies. 
We also present the SABL and I-SABL algorithms, which consider multiple interpretations of trainer feedback in order to learn 
behaviors more efficiently. Our online user studies show that human trainers follow various training strategies when teaching 
virtual agents and explicitly considering trainer strategy can allow a learner to make inferences from cases where no feedback is given.

- <b>Related Papers:</b>
  > <b>Learning behaviors via human-delivered discrete feedback: modeling implicit feedback strategies to speed up learning</b> <br>
Robert Loftin, Bei Peng, James MacGlashan, Michael L. Littman, Matthew E. Taylor, Jeff Huang, and David L. Roberts. <i>Journal of Autonomous Agents and Multi-Agent Systems, pages 1-30, 2015. </i>[[pdf]](http://beipeng.github.io/files/2015aamas-loftin.pdf)

  > <b>Learning Something from Nothing: Leveraging Implicit Human Feedback Strategies</b> <br>
Robert Loftin, Bei Peng, James MacGlashan, Michael Littman, Matthew E. Taylor, David Roberts, and Jeff Huang. <i>In Proceedings of the 23rd IEEE International Symposium on Robot and Human Interactive Communication (RO-MAN), August 2014. </i>[[pdf]](http://beipeng.github.io/files/2014roman-loftin.pdf)

  > <b>A Strategy-Aware Technique for Learning Behaviors from Discrete Human Feedback</b> <br>
Robert Loftin, James MacGlashan, Bei Peng, Machiael L. Littman, Matthew E. Taylor, Jeff Huang, and David L. Roberts. <i>In Proceedings of the 28th AAAI Conference on Artificial Intelligence (AAAI), July 2014. </i>[[pdf]](http://beipeng.github.io/files/2014aaai-loftin.pdf)


### Training an Agent to Ground Commands with Reward and Punishment
As increasing need for humans to convey complex tasks to robots without any technical expertise, conveying tasks through 
natural language provides an intuitive interface. But it needs the agent to learn a grounding of natural language commands. 
In this work, we developed a simple simulated home environment in which the robot needs to complete some tasks via learning 
from human positive or negative feedback.

- <b>Related Papers:</b>
  > <b>Language and Policy Learning from Human-delivered Feedback</b> <br>
Bei Peng, Robert Loftin, James MacGlashan, Michael L. Littman, Matthew E. Taylor, and David L. Roberts. <i>In Proceedings of the Machine Learning for Social Robotics workshop (at ICRA), May 2015. </i>[[pdf]](http://beipeng.github.io/files/2015icra-peng.pdf)


### Agent Corrections to Pac-Man from the Crowd
Reinforcement learning suffers from poor initial performance. Our approach uses crowdsourcing to provide non-expert suggestions 
to speed up learning of an RL agent. Currently, we are using Mrs. Pac-Man as our application domain for its popularity as a game. 
From our studies, we have already concluded that crowdsourcing, although non-experts, are good in identifying mistakes. We are now 
working on how we can integrate the crowd’s advice to speed up the RL agent’s learning. In the future, we intend to implement this 
approach to a physical robot.

- <b>Related Papers:</b>
  > <b>Towards Integrating Real-Time Crowd Advice with Reinforcement Learning</b> <br>
Gabriel V. de la Cruz Jr., Bei Peng, Walter S. Lasecki, and Matthew E. Taylor. <i>In The 20th ACM Conference on Intelligent User Interfaces (IUI), Poster Session, March 2015. </i>[[pdf]](http://beipeng.github.io/files/2015iui-delacruz.pdf)

  > <b>Generating Real-Time Crowd Advice to Improve Reinforcement Learning Agents</b> <br>
Gabriel V. de la Cruz Jr., Bei Peng, Walter S. Lasecki, and Matthew E. Taylor. <i>In Proceedings of the Learning for General Competency in Video Games workshop (AAAI), January 2015. </i>[[pdf]](http://beipeng.github.io/files/2015aaai-delacruz.pdf)
