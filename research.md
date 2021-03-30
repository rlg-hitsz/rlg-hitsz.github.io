---
layout: page
title: Research
---

<p align="center">
<img src="/research/r1.jpg" alt="" width="800" />
</p>

Our research focus on the theory of Reinforcement Learning, Inverse Reinforcement Learning, Decision and Optimization, and their applications in  UAV control, unmanned driving system and warehousing robot scheduling.

Feel free to contact us if you are interested in some of these projects.

------

### Unmanned Warehouse Robot

In the field of logistics, the optimal scheduling of warehousing robots has always been a challenge. Given a handling task, how to schedule warehouse robots so that they can complete the task in the shortest time? How to use the minimum power consumption to finish the given task? And, how to use the least number of robots to complete a given task within the specified time? These all are the issues that we should consider. In the next few years, powered by the strong decision-making ability of RL algorithms, our group will focus on this problem, making warehouse robots smarter and more powerful.

<p align="center">
<img src="/research/AGV-1.jpg" alt="" width="540" />
<img src="/research/AGV-2.jpg" alt="" width="540" />
</p>

------

### Safe Reinforcement Learning

Limited to the paradigm of trial and error, reinforcement learning algorithms have not been widely applied in practice, especially in scenes with physical objects. This is because, when training an agent, a random policy may lead to unpredictable actions which will result in physical damage. So, the idea of safe reinforcement learning was proposed to tackle this challenge. Safe RL can be defined as the process of learning policies that maximize the expectation of the return in problems in which it is important to ensure reasonable system performance and/or respect safety constraints during the learning and/or deployment processes. At present, the development of safe reinforcement learning algorithms is relatively preliminary, most of which only reduce the probability of unsafe behavior in the process of exploitation. Therefore, an important research topic of our group is safe reinforcement learning, and we committe to applying reinforcement learning algorithms to various industries.

------

### Recognition of Pedestrains' Intentions Based on Machine Learning

Nowadays, robots are in an increasingly complex working environment with the development of intelligent robots, and the correct navigation of robots is especially significant when there are numerous pedestrians. However, the unobservability of pedestrians’ behavioral intentions greatly increases the difficulty of robot navigation. The uncertainty of navigation can be effectively reduced if we can infer the behavioral intentions of pedestrians thus how to infer the intentions and trajectories of pedestrians from observable sequences becomes a problem that needs to be solved. Unlike conventional vision-based intent recognition methods that rely on cameras and laser sensors, in this paper, we obtained observation data based on Microsoft Kinect depth sensor, and for modeling, we used a traditional Hidden Markov Models (HMMs). The training data we used was collected by ourselves. In the experiment, we tested several possible interactions between pedestrians, analyzed and predicted their possible intentions, and summarized the experimental results. The results show that the model can predict the pedestrians’ intentions in general, but it is limited by the maximum distance of depth and field of the Kinect depth image. Therefore, this method still has a large room for improvement.

<p align="center">
<iframe width="360" height="240" src="https://www.youtube.com/embed/jkG9D5aZfy0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="360" height="240" src="https://www.youtube.com/embed/SEdIfquZ-vM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="360" height="240" src="https://www.youtube.com/embed/dZ4KVu-HF-I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

------

### Real-Time UAV Target Tracking

In this project, we present a complete strategy of tracking a ground moving target in complex indoor and outdoor environments with an unmanned aerial vehicle (UAV) based on computer vision. The main goal of this system is to track a ground moving target stably and get the target back when it is lost. An embedded camera on the UAV platform is used to provide real-time video stream to the onboard computer where the target recognition and tracking algorithms are running. A vision-based position estimator is applied to localize the position of UAV. According to the position of the ground target obtained from the 2-dimensional images, corresponding control strategy of the UAV is implemented. Simulation of UAV and ground moving target with the target-tracking system is performed to verify the feasibility of the mission. After the simulation verification, a series of real-time experiments are implemented to demonstrate the performance of the target-tracking strategy.

<p align="center">
<iframe width="540" height="300" src="https://www.youtube.com/embed/usDHdOXneig?rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="540" height="300" src="https://www.youtube.com/embed/AmQ-6F1Wh_o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

------