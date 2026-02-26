---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
---

## Text-to-SQL

As the size and complexity of databases continue to grow, managing and querying them manually becomes increasingly infeasible. Our lab is designing advanced large language model (LLM)-powered multi-agent systems that serve as natural language interfaces to databases, making it possible to query and retrieve information seamlessly using everyday language.
Three notable contributions from our lab in this domain are CHESS, CHASE-SQL, and Reasoning-SQL, each introducing innovative approaches to tackling challenges in text-to-SQL synthesis.

### Chess: Contextual Harnessing for Efficient SQL Synthesis (ICML 2025, MAS workshop)

CHESS framework addresses key challenges such as large database schemas, ambiguous natural language questions, and ensuring functional validity of queries. CHESS leverages a multi-agent architecture, including components like the Information Retriever, Schema Selector, Candidate Generator, and Unit Tester, to generate accurate, privacy-preserving SQL queries.
It efficiently handles industrial-scale databases by narrowing schemas, reducing computational cost, and supporting deployment in privacy-sensitive environments. CHESS demonstrates remarkable scalability, achieving near state-of-the-art performance with significantly fewer computational resources.

Paper: [https://arxiv.org/abs/2405.16755](https://arxiv.org/abs/2405.16755)

Code: [https://github.com/ShayanTalaei/CHESS](https://github.com/ShayanTalaei/CHESS)

### Chase-SQL: Multi-Path Reasoning and Preference Optimized Candidate Selection in Text-to-SQL (ICLR 2025)

The CHASE-SQL framework further advances text-to-SQL research through multi-path reasoning and preference-optimized candidate selection. By employing diverse LLM generators, including methods such as divide-and-conquer query decomposition, chain-of-thought reasoning, and instance-aware synthetic example generation, CHASE-SQL generates robust SQL candidates. A dedicated selection agent then identifies the optimal query through pairwise comparisons.
This framework achieves state-of-the-art execution accuracy on the BIRD benchmark, setting new standards in query quality and diversity while outperforming other methods.

Paper: [https://arxiv.org/abs/2410.01943](https://arxiv.org/abs/2410.01943)

---

## SPRINT: Enabling Interleaved Planning and Parallelized Execution in Reasoning Models

Large reasoning models (LRMs) have transformed AI's ability to tackle intricate tasks but often face significant performance bottlenecks due to their inherently sequential reasoning processes. To overcome these limitations, our lab developed SPRINT, a groundbreaking framework designed to enable LRMs to dynamically recognize opportunities for parallelization within their reasoning chains.
By reorganizing reasoning trajectories into structured rounds of strategic planning and parallel execution, SPRINT enables models to efficiently decompose complex tasks into manageable subtasks, significantly reducing inference time. Evaluations demonstrate that SPRINT-enhanced models achieve comparable accuracy to traditional LRMs while drastically shortening the sequential generation of reasoning steps.
This approach not only streamlines model performance on complex problems but also opens new pathways for faster, scalable reasoning across diverse applications.

Paper: [https://arxiv.org/abs/2506.05745](https://arxiv.org/abs/2506.05745)

---

## StorySage: Conversational Autobiography Writing Powered by a Multi-Agent Framework

Everyone has a story worth telling, but turning a lifetime of memories into a cohesive autobiography can be challenging. Our lab aims to bridge this gap through StorySage, an innovative conversational system that guides users in documenting their personal journeys. StorySage is built upon a multi-agent framework designed to emulate meaningful, structured, and adaptive conversations.
By engaging users naturally and iteratively, the system collects and organizes their memories into a rich, evolving narrative. Through this personalized, user-centered approach, StorySage not only simplifies the autobiographical writing process but also deepens user engagement, ultimately enabling people to preserve their unique life stories in a more intuitive and fulfilling way.

Paper: [https://arxiv.org/abs/2506.14159](https://arxiv.org/abs/2506.14159)

---

## MAGNOLIA: Matching Algorithms via GNNs (ICML 2024)

Online Bayesian bipartite matching is a central problem in digital marketplaces and exchanges, including advertising, crowdsourcing, ridesharing, and kidney exchange. We introduce a graph neural network (GNN) approach that emulates the problem's combinatorially-complex optimal online algorithm, which selects actions (e.g., which nodes to match) by computing each action's value-to-go (VTG) -- the expected weight of the final matching if the algorithm takes that action, then acts optimally in the future.
We train a GNN to estimate VTG and show empirically that this GNN returns high-weight matchings across a variety of tasks. Moreover, we identify a common family of graph distributions in spatial crowdsourcing applications, such as rideshare, under which VTG can be efficiently approximated by aggregating information within local neighborhoods in the graphs. This structure matches the local behavior of GNNs, providing theoretical justification for our approach.

Paper: [https://arxiv.org/abs/2406.05959](https://arxiv.org/abs/2406.05959)

---

## A Local Limits Perspective on GNNs

We propose a theoretical framework for training Graph Neural Networks (GNNs) on large input graphs via training on small fixed-size sampled subgraphs. This framework is applicable to a wide range of models, including popular sampling-based GNNs, such as GraphSAGE and FastGCN.
Leveraging the theory of graph local limits, we prove that, under mild assumptions, parameters learned from training sampling-based GNNs on small samples of a large input graph are within an ϵ-neighborhood of the outcome of training the same architecture on the whole graph. We derive bounds on the number of samples, the size of the graph, and the training steps required as a function of ϵ. Our results give a novel theoretical understanding for using sampling in training GNNs.
They also suggest that by training sampling-based GNNs on small samples of the input graph, practitioners can identify and select the best models, hyperparameters, and sampling algorithms more efficiently. We empirically illustrate our results on a node classification task on large citation graphs, observing that sampling-based GNNs trained on local subgraphs 12× smaller than the original graph achieve comparable performance to those trained on the input graph.

Paper: [https://arxiv.org/abs/2310.10953](https://arxiv.org/abs/2310.10953)
