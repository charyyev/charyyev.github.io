---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Master’s student in Computer Science at [ETH Zurich](https://ethz.ch/de.html), Switzerland, specializing in robotics and computer vision. My master’s thesis focused on developing efficient multimodal environment representations for robot navigation, where I designed a novel architecture and self-supervised learning method to enhance perception tasks.

My passion for computer vision began during my undergraduate studies, where I worked as a research assistant at the [AI, Robotics and Transportation lab](https://chiuau.github.io/), contributing to autonomous drone racing research. After graduation, I gained industry experience as a Machine Learning Research Engineer Intern at [Seoul Robotics](https://seoulrobotics.tech/) and as a Perception Engineer at [STPC](http://ar247.co.kr/), where I worked on LiDAR based perception.



<!-- Publications
======
### 2024 

Philip Toma, **Olga Ovcharenko**, Imant Daunhawer, Julia E. Vogt, Florian Barkmann, Valentina Boeva: Benchmarking Self-Supervised Learning for Single-Cell Data [[paper]](https://www.biorxiv.org/content/10.1101/2024.11.04.620867v1.full.pdf) [[poster]](poster.pdf). NeurIPS [SSL Workshop](https://sslneurips2024.github.io) 2024.

**Olga Ovcharenko**, Rita Sevastjanova, Valentina Boeva: FeatureClock: High-Dimensional Effects in Two-Dimensional Plots [[library]](https://pypi.org/project/feature-clock/) [[paper]](https://arxiv.org/abs/2408.01294) [[slides]](FeatureClock.pdf). IEEE VIS 2024.


### 2022 

Sebastian Baunsgaard, Matthias Boehm, Kevin Innerebner, Mito Kehayov, Florian Lackner, **Olga Ovcharenko**, Arnab Phani, Tobias Rieger, David Weissteiner and Sebastian Benjamin Wrede: Federated Data Preparation, Learning, and Debugging in Apache SystemDS [[paper]](https://dl.acm.org/doi/10.1145/3511808.3557162). CIKM 2022.


### 2021

Sebastian Baunsgaard, Matthias Boehm, Ankit Chaudhary, Behrouz Derakhshan, Stefan Geißelsöder, Philipp M. Grulich, Michael Hildebrand, Kevin Innerebner, Volker Markl, Claus Neubauer, Sarah Osterburg, **Olga Ovcharenko**, Sergey Redyuk, Tobias Rieger, Alireza Rezaei Mahdiraji, Sebastian Benjamin Wrede, Steffen Zeuch:
ExDRa: Exploratory Data Science on Federated Raw Data [[paper]](https://dl.acm.org/doi/10.1145/3448016.3457549).
SIGMOD 2021. -->

Work Experience
======
- Master's Thesis - [Robotic Systems lab](https://rsl.ethz.ch/). Mar - Oct 2024
- Research Assistant (Remote Sensing)  - [ETH Zurich](https://ethz.ch/de.html). Apr 2023 - Dec 2024 
- Perception Engineer - [STPC](http://ar247.co.kr/). Mar - Sep 2022 
- Machine Learning Research Engineer Intern - [Seoul Robotics](https://seoulrobotics.tech/). Sep 2021 - Feb 2022
- Research Assistant - [ART lab](https://chiuau.github.io/). Sep 2019 - Aug 2021
- Research Assistant - [Data Science lab](https://www.ibs.re.kr/eng/sub02_02_02_02.do). Jul - Aug 2019
- Teaching Assistant (Calculus I & II) - [UNIST](https://www.unist.ac.kr/). Sep 2018 - Jun 2021

Education
======
- Master of Science, Computer Science at [ETH Zurich](https://ethz.ch/de.html), 2022 - 2024
  - Thesis: Efficient Multimodal Environment Representation for Robot Navigation [thesis](papers/thesis.pdf)
- Bachelor of Science, Computer Science and Mathematics at [UNIST](https://www.unist.ac.kr/), 2017 - 2021

Projects
======

## Semantic-MD: Infusing Monocular Depth with Semantic Signals 
[paper](papers/3DV_Paper_Charyyev_Ghosh_Lemke.pdf) [code](https://github.com/charyyev/semantic_md)

Monocular depth estimation (MDE) plays a crucial role
in numerous computer vision tasks, such as 3D reconstruction, 
scene understanding, and augmented reality. However, as MDE 
is an ill-posed problem, the incorporation
of additional semantic cues can facilitate improved depth
estimation. In this paper, we explore different techniques
based on deep learning to leverage the rich semantic details
present in an image for monocular depth estimation. 
First, we explore different ways of integrating semantic 
signals to the input in the form of semantic maps
and borders. Second, we jointly estimate depth and semantic 
maps to exploit the complementary nature of thesetasks. 
We conduct extensive ablation studies for both of our approaches
with different semantic signals and loss functions 
and compare them with our encoder-decoder based
baseline architecture. We validate our results quantitatively 
through various evaluation metrics, and qualitatively
on HyperSim dataset.

## Urban Growth Unveiled: Deep Learning with Satellite Imagery for Measuring 3d Building-Stock Evolution in Urban China 
[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4967121)

Time-series information on building stock is of paramount importance to study cities in a host of disciplines ranging from economics to urban planning and sociology. Such data are lacking in a consistently measured way and especially among dynamically growing cities in developing countries. Due to their rapid change, building stock data in these cities can offer insight into the determinants and consequences urbanisation. To be able to analyze urban structures effectively, the building stock needs to be measured with sufficient detail -- at a resolution that makes individual buildings or small conglomerates thereof visible -- and it needs to consider building height (volume) with a satisfactory scope across cities to cover both large numbers and multi-year sequences of data. This study aims to develop a comprehensive pipeline for predicting building volume -- including both footprint and height -- across 1,537 urban areas in mainland China, covering more than 60% of the Chinese population over a seven-year period (2017-2023). With the advancement of deep learning in remote sensing and computer vision, we can leverage state-of-the-art techniques to produce large-scale data for Chinese cities across years, which could be otherwise time-consuming with traditional remote-sensing techniques.We demonstrate that the proposed approach leads to credible metrics of both footprint and height predictions and performs very competitively with respect to existing building-volume predictions. We also benchmark our results against other data sources such as real-estate listings and demonstrate the out-of-sample prediction capability of our proposed model.

## Computational Intelligence Lab - Road Segmentation
[paper](papers/road_segmentation.pdf)
Road segmentation from aerial images is an important 
problem that has applications in urban planning,
infrastructure development, and transportation. This paper
presents our solution for the ETHZ CIL Road Segmentation
2023 challenge which requires segmenting roads in images
obtained from google maps. Starting from a U-net baseline, we
propose to replace its encoder with an EfficientNet-b7 encoder
to increase its capacity. Additionally, to deal with data scarcity
we propose to use a pretraining strategy, data augmentation,
ensemble learning, and test time augmentation. We further
refine the results with Conditional Random Fields. With all
these components, our solution demonstrates promising results
in aerial road segmentation.


Awards
======
- International Mathematics Olympiad 2016 - Honorable Mention
- International Zhautykov Olympiad 2016 - Bronze Medal
- Mediterranean Mathematical Competition 2016 - Gold Medal
- National Olympiad 2016  - Silver Medal

