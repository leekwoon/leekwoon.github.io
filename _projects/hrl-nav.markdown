---
layout: page
title: hrl-nav
description: Adaptive and Explainable Deployment of Navigation Skills via Hierarchical Deep Reinforcement Learning
img: /assets/img/projects/hrl-nav/example.gif
importance: 2
type: research
---

<h3 style="text-align: center;font-size:30px">Adaptive and Explainable Deployment of Navigation Skills via Hierarchical Deep Reinforcement Learning</h3>
<h4 style="text-align: center;color:DodgerBlue"> <b>Kyowoon Lee</b>*, Seongun Kim*, Jaesik Choi </h4>
<h5 style="text-align: center;"> ICRA 2023 </h5>
<h5 style="text-align: center;color:gray"> (*: equal contribution) </h5>
<h5 style="text-align: center;color:gray">
    <a style="color:DodgerBlue" href="">[Paper(will be appeared)]</a>
    <a style="color:DodgerBlue" href="https://github.com/leekwoon/hrl-nav">[Code]</a>
</h5>


<video width="800" playsinline="True" autoplay="True" muted="True" controls>
  <source src="/assets/img/projects/hrl-nav/ICRA23_2983_VI_fi.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

## **Abstract**

For robotic vehicles to navigate robustly and safely in unseen environments, it is crucial to decide the most suitable navigation policy. However, most existing deep reinforcement learning based navigation policies are trained with a hand-engineered curriculum and reward function which are difficult to be deployed in a wide range of real-world scenarios. In this paper, we propose a framework to learn a family of low-level navigation policies and a high-level policy for deploying them. The main idea is that, instead of learning a single navigation policy with a fixed reward function, we simultaneously learn a family of policies that exhibit different behaviors with a wide range of reward functions. We then train the high-level policy which adaptively deploys the most suitable navigation skill. We evaluate our approach in simulation and the real world and demonstrate that our method can learn diverse navigation skills and adaptively deploy them. We also illustrate that our proposed hierarchical learning framework presents explainability by providing semantics for the behavior of an autonomous agent.

## **Contribution**

* Proposal of a hierarchical reinforcement learning ap-
proach which learns diverse navigation skills and de-
ploys them.
* Extensive evaluation of our approach on various sce-
narios including a real-world robot navigation which
demonstrates effectiveness and explainability of our
approach.
