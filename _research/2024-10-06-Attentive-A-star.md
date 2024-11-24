---
title: "Attentive A* for Visual Cue Based Path Planning in Complex Environments"
collection: research
custom: 'true'
custom_remark: "Accepted at ECAI'24 Workshop on Agents and Robots for Reliable Engineered Autonomy (AREA)"
permalink: /research/attentiveastar
excerpt: "This paper introduces Attentive A* incorporating attention mechanism into data-driven path-planning algorithms. This algorithm makes use of SCSE mechanism along with VGG-19 in the encoder part of the algorithm to generate a guidance map.

Download/View [here](https://link.springer.com/chapter/10.1007/978-3-031-73180-8_9)"
# date: 2024-10-06
# venue: "ECAI'24 Workshop on Agents and Robots for reliable Engineered Autonomy (AREA)"
---

<style>

/* Style the counter cards */
.card {
<!--   box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */ -->
  padding: 16px;
<!--   text-align: center; -->
<!--   background-color: #f1f1f1; -->
}

a:link {
  text-decoration: none;
}
</style>

Navigating through complex environments has always been a big challenge for smart robots and AI agents. This paper focuses on a specific problem within the domain of path planning, aiming to aid agents in navigating through intricate environments using raw images as input. Data-driven path-planning algorithms have emerged as a cogent solution to such problems. These algorithms are a fusion of deep learning models for cost approximation, and differentiable versions of classical planning algorithms. While these methods excel at handling combinatorial data, their computational demands are high. These often leads to poor function approximation due to ineffective feature extraction in complex environments. Drawing from the significance of the attention mechanism in various deep learning applications, we present Attentive A*, introducing attention to data-driven path-planning algorithms. The proposed approach provides precise cost approximations by leveraging visual cues, resulting in enhanced performance across various metrics. A comprehensive assessment is conducted on diverse datasets, including MP, Tiled MP, CSM and Warcraft, to assess the effectiveness of the proposed approach compared to other baselines. 

Paper [here](https://link.springer.com/chapter/10.1007/978-3-031-73180-8_9)