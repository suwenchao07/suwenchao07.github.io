---
title: 'A deep reinforcement learning based searching method for source localization'
layout: pub
classification: publications
date: 2021-12-29 00:00:00 +0000
excerpt: The localization of hazardous sources (e.g. poisonous gas sources) is an important task regarding the security of human society. To find the unknown source in time, various autonomous source searching methods have mushroomed and been employed over the past decade. This paper designs a fresh source searching approach, namely particle clustering-deep Q-network, PC-DQN, which applies the deep reinforcement learning (DRL) techniques as a source searching approach for the first time. Specifically, the search process is formulated as the partially observable Markov decision process, then converted into the Markov decision process based on the belief state (represented by the particle filter).
link: https://www.sciencedirect.com/science/article/abs/pii/S0020025521012615
year: 2021
author: Yong Zhao, Bin Chen, XiangHan Wang, Zhengqiu Zhu, Yiduo Wang, Guangquan Cheng, Rui Wang, Rongxiao Wang, Ming He, Yu Liu
journal: Information Sciences
content_img: "/uploads/2022/12/newd.jpg"
author_img: ''
tags: Source
portfolio-type:
- type: "Source"
- type: "illustration"
- type: "publications"
weight: JCR二区
authorFirst: 季雅泰
correspondingAuthor: hua he
searchStatus:  SCI/EI
searchNumber: 10.1021/acs.jpclett.3c00672
impactFactors: 8.6
database: Web of Science
---
Abstract

The localization of hazardous sources (e.g. poisonous gas sources) is an important task regarding the security of human society. To find the unknown source in time, various autonomous source searching methods have mushroomed and been employed over the past decade. This paper designs a fresh source searching approach, namely particle clustering-deep Q-network, PC-DQN, which applies the deep reinforcement learning (DRL) techniques as a source searching approach for the first time. Specifically, the search process is formulated as the partially observable Markov decision process, then converted into the Markov decision process based on the belief state (represented by the particle filter). PC-DQN leverages the density-based spatial clustering of applications with noise (DBSCAN) algorithm to extract the feature of belief state, and employ the deep Q-network (DQN) algorithm to find the optimal policy for the source searching task. Through the comparison with two baseline methods (i.e. RANDOM and Entrotaxis algorithm) under various experimental conditions, the viability of our proposed PC-DQN is testified. Results explicitly reveal that the success rate of the PC-DQN maintains at a high level (beyond 99.6%) in all scenarios in this paper, and the mean search step shows evident superiority over baseline methods in most scenarios. Significantly, we also introduce the transfer learning concept to reuse the well-trained Q-network into new scenarios. These findings show important implications of the DRL-based approach as an alternative and more effective source searching approach.