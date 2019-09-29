---
title: "Deep Learning for Robot Locomotion"
excerpt: "We explore ways in which deep reinforcement learning can be used to help underactuated and unintuitive robots learn locomotion tasks, ranging from gait discovery to path planning."
collection: research
permalink: /research/deep-learning
---

Recent developments have seen an explosion in the usage of deep reinforcement learning (DRL) techniques to all sorts of applications. Heavy computing requirements, the usage of large amounts of data, and long training times are all still prohibitive challenges for implementation of DRL on physical robots, particularly lightweight and mobile systems. We are interested in combining simple analytical models of robot locomotion (for example, using geometric mechanics) with more lightweight and "user-friendly" DRL techniques to learn original gaits and follow specified paths.

The intuitions gained from geometric mechanics, such as symmetries exhibited by a robot, can help inform design decisions for a DRL algorithm, such as the states to track, allowable actions, and reward function parameterization. For example, we consider using the popular Deep Q-Network (DQN) algorithm to learn simple gaits to move the swimming three-link robot above in a forward direction. Two such results are obtained and overlaid on a joint space plot below. While they are not identical, they are equally effective in producing forward displacement. One is learned in 2M iterations without reductions from the geometric model of the robot, while the other utilizes reductions and is learned in only 5k iterations, a difference of 4000 times.

Ultimately, we hope that such drastic reductions in learning effort will make it feasible for robots to physically learn locomotion tasks in the real world without a need for simulation and human input. 
