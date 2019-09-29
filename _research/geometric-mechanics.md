---
title: "Geometric Mechanics of Robot Locomotion"
excerpt: "We explore ways in which ideas and techniques from geometric mechanics can be applied to underactuated and dynamic robot systems with an eye toward locomotion."
collection: research
permalink: /research/geometric-mechanics
---

Two challenges in developing unified controllers for robot locomotion include the diversity of robot models and the complexity that a robot can exhibit in terms of high dimensionality, nonlinearity, and underactuation. The application of geometric mechanics to robotics aims to improve transferrability of techniques for robot locomotion to a broad class of systems. At the heart of these ideas is the identification of symmetries in a robot's mathematical model, simultaneously bringing together physically different types of robots under the same umbrella and reducing their complexity. In this representation, it is possible to reduce the problem of planning gaits for the snake robot shown below to the more analytical task of finding closed curves on so-called curvature plots.

In the spirit of extending the usefulness of geometric mechanics to more general systems, we consider modifications that must be made in the face of loss of symmetries or dynamic effects. For example, the replacement of the snake robot's rear joint motor with a passive spring makes the system dynamic and immediately complicates the model. However, we can extend the analysis of the "fully actuated" robot to this new one, allowing us to locomote the partially actuated robot just as effectively as its predecessor. This is useful for modeling such a robot with even more links as well, as shown in our robot navigation video below.

Other examples of geometric applications for dynamic robots include systems interacting with the ambient medium. This is particularly relevant for swimming robots that interact with the surrounding fluid and with each other via the fluid. Applications include the generation of gaits and motion controllers that synchronize locomotion in such environments
