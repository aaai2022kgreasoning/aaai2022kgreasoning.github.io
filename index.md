## AAAI 2022 Tutorial: Reasoning on Knowledge Graphs: Symbolic or Neural?

This is the website of the AAAI 2022 tutorial, Reasoning on Knowledge Graphs: Symbolic or Neural?

### Introduction

Knowledge graphs encode real-world facts and are critical in a variety of applications and domains such as natural language understanding, recommender systems, drug discovery, and image understanding. A fundamental problem on knowledge graphs is to predict missing facts by reasoning with existing facts, a.k.a. knowledge graph reasoning. Such a problem has been extensively studied in different communities of AI including general AI community (AAAI, IJCAI), machine learning community (ICML, NeurIPS, ICLR), data mining community (KDD, WSDM, WWW), and NLP community (ACL, EMNLP, NAACL), which either focus on development of fundamental methodology or solutions to important real-world problems. Therefore, a systematic introduction to knowledge graph reasoning summarizing the progress across different communities would benefit broad audience. In this tutorial, we plan to give a comprehensive introduction to different methods of knowledge graph reasoning, including traditional symbolic logic rule-based methods, neural-based methods, neural-symbolic methods, logic rule induction approaches, and different \emph{applications}. This tutorial will benefit both junior and senior researchers and researchers interested in both methodology development and applications.

### Outline

* Introduction
* Part 1: Neural Methods

  * Knowledge graph embeddings

    * TransE, ComplEx, RotatE, QuatE

  * Graph neural networks

    * RGCN, GraIL

  * Benchmark datasets and evaluation
* Part 2: Symbolic Logic Methods

  * Logic programming

    * Forward chaining, backward chaining

  * Bayesian logic programming

    * ProbLog, DeepProbLog

  * Markov logic programming

    * Marlov logic networks

  * Stochastic logic programming

    * TensorLog
* Part 3: Neural-Symbolic Methods

  * Markov logic programming based

    * pLogicNet

  * Stochastic logic programming based

    * ProPPR
* Part 4: Logic Rule Induction Methods

  * Inductive logic programming
  * Neural-powered ILP

    * Differentiable ILP, Neural Theorem Provers, RNNLogic
  * Neural ILP with SLP

    * NeuralLP, DeepPath, NBFNet
* Part 5: Summary and Future Directions
  * Summary
  * Complex logical query answering
  * Natural language processing
  * Recommendation
  * Drug discovery

### Speakers

* [Meng Qu](https://mnqu.github.io/)
  * meng.qu at umontreal.ca
  * Meng Qu is a 4th-year Ph.D. candidate at Mila - Quebec AI Institute, supervised by Prof. Jian Tang. His research focuses on reasoning on graph structured data such as knowledge graphs. He obtained M.Sc. in computer science from University of Illinois at Urbana-Champaign and B.Sc. in computer science from Peking University. He has published several papers on combining deep learning and statistical relational learning for knowledge reasoning in top-tier venues, including GMNN at ICML 2019, pLogicNet at NeurIPS 2019, RNNLogic at ICLR 2021. 
* [Zhaocheng Zhu](https://kiddozhu.github.io/)
  * Zhaocheng.zhu at umontreal.ca
  * Zhaocheng Zhu is currently a 4th-year Ph.D. candidate at Mila - Quebec AI Institute, advised by Prof. Jian Tang. His research mainly focuses on large-scale knowledge graphs, including algorithms and systems for knowledge graph reasoning, as well as applications of knowledge graphs in drug discovery. He received his B.Sc. in computer science (with honors) from Peking University in 2018. He has been actively working on knowledge graphs and graph representation learning since 2018, with two publications in top-tier venues. He led 2 open-source projects, GraphVite and TorchDrug, which has received wide recognition in the graph representation learning community. He is also a contributor of PyTorch-Geometric and Gensim.
* [Jian Tang](https://jian-tang.com/)
  * Jian.tang at hec.ca
  * Jian Tang is currently an assistant professor at Mila - Quebec AI Insitute, a research institute focusing on deep learning and reinforcement learning led by Turing Award Winner Yoshua Bengio, starting from December 2017. His research focuses on graph representation learning, graph neural networks, drug discovery, and knowledge graphs. He is named the first cohort of Canada CIFAR Artificial Intelligence Chairs (CIFAR AI Research Chair). He was a research fellow in University of Michigan and Carnegie Mellon University. He was a researcher in Microsoft Research Asia for two years. He received the best paper award of ICML’14 and nominated for the best paper of WWW’16. Most of his papers are published in top-tier venues across artificial intelligence, machine learning and data mining conferences (ICML, NeurIPS, ICLR, AAAI, IJCAI, KDD, WWW, and WSDM). He co-organized a tutorial on graph representation learning at KDD 2017 and AAAI 2019, organized a few workshops on graph representation learning at SDM 2019, CIKM 2019, AAAI 2020, and ICML 2020. He published quite a few representative work on graph representation learning (including LINE, LargeVis, RotatE). 
