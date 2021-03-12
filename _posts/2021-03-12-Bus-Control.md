---
layout:     post
title:      Dynamic holding control to avoid bus bunching, A multi-agent deep reinforcement learning framework
author:     Jiawei Wang
tags: 		post RL Transit 
subtitle:  	
category:   research
---

## Authors
Jiawei Wang, Lijun Sun

## Abstract 

Bus bunching has been a long-standing problem that undermines the efficiency and reliability of public transport services. The most popular countermeasure in practice is to introduce static and dynamic holding control. However, most previous holding control strategies mainly consider local information with a pre-specified headway/schedule, while the global coordination of the whole bus fleet and its long-term effect are often overlooked. To efficiently incorporate global coordination and long-term operation in bus holding, in this paper we propose a multi-agent deep reinforcement learning (MDRL) framework to develop dynamic and flexible holding control strategies for a bus route. Specifically, we model each bus as an agent that interacts with not only its leader/follower but also all other vehicles in the fleet. To better explore potential strategies, we develop an effective headway-based reward function in the proposed framework. In the learning framework, we model fleet coordination by using a basic actor-critic scheme along with a joint action tracker to better characterize the complex interactions among agents in policy learning, and we apply proximal policy optimization to improve learning performance. We conduct extensive numerical experiments to evaluate the proposed MDRL framework against multiple baseline models that only rely on local information. Our results demonstrate the superiority of the proposed framework and show the promise of applying MDRL in the coordinative control of public transport vehicle fleets in real-world operations.

You can find the full paper [here](https://www.sciencedirect.com/science/article/pii/S0968090X20305763).

## Video
[![Watch the video](https://smart-transport.github.io/img/projects/bus_holding01.png)](htt