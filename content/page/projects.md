---
title: "Projects"
date: 2022-09-06T03:48:01-07:00
categories:
tags:
keywords:
- tech
comments:       false
showMeta:       false
showActions:    false
#thumbnailImage: //example.com/image.jpg
---
## FSE Emergency Social Network
![FSE ESN](/images/projects/ESN.png)
Emergency Social Network is a chat room based web application for citizen to exchange information during covid-19.
This project contains several high-level requirements: Join Community, Login-Logout, Chat Publicly/Privately, Post Announcement, Share Status, Search Information, Administer User Profile, Health Report Generator, Covid-19 Map/Article Inventory/Supplies.
And the following tech stacks are used:
- web UI frontend: PUG(HTML)/CSS with bootstrap, jquery
- backend: node.js
- database: mongoDB
- unit-test framework: jest

And this application is deployed on heroku with CircleCI

## Sample application on internal AKS cluster
In this project, I deployed sample application on Kubernetes cluster, established pipeline to manage Docker and patch
K8s, and integrated Observability tools including Grafana and Prometheus. Created tutorial to help
developers migrating system and saved 50% learning time.

## User Activity Analysis System
This project is a backend infrastructure to collect and analyze website users using JavaScript, Python, PHP,
MongoDB, MySQL and AWS.

## DTS with DSP on television SoC
This project is to port [DTS](https://dts.com/dtsx/) sound effect algorithm in C embedding programming on television SoC with Tensilica Hifi2/Hifi4 DSP and finally surpassed 4x speedup for audio processing.


## Master Thesis
**End-to-end Pinyin to Character Language Model using Self-Attention Mechanism**  
*Advisor: Prof. Sin-Horng Chen, Prof. Yih-Ru Wang*

Deep neural network with conventional automatic speech recognition (ASR) structure improve the performance significantly in recent years. And end-to-end ASR achieve competitive performance as well with huge amount of data and computing resources. This study focused on end-to-end language model, training an end-to-end language model by sequence labeling method and self-attention seq2seq model (Transformer) which are common method in some NLP task. The dataset included syllable sequence converted from 440 million words Chinese corpus through a proposed G2P system. And the syllable to character model with transformer achieved lower character error rate than the baseline trigram model in the external test set.