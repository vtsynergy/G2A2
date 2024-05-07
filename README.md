# G2A2: Graph Generator with Attributes and Anomalies

Many data-mining applications use dynamic attributed graphs to represent relational information; but due to security and privacy concerns, there is a dearth of publicly available datasets that can be represented as dynamic attributed graphs. Even when such datasets are available, they do not have ground truth that can be useful for classification problems, e.g., anomaly detection. Thus, researchers commonly generate synthetic graphs using either statistical or deep generative (DG) methods. However, neither approach produces ground truth. Statistical methods struggle to replicate intricate patterns found in real-world dynamic attributed graphs, while DG methods require a significant number of graphs for training. 

To address these shortcomings, we present G2A2, an automated <ins>g</ins>raph <ins>g</ins>enerator with <ins>a</ins>ttributes and <ins>a</ins>nomalies, which encompasses (1) probabilistic models to generate a dynamic bipartite graph, representing realistic time-evolving connections between two independent sets of entities, (2) realistic injection of anomalies for ground truth using a novel algorithm that captures the general properties of graph anomalies across domains, and (3) generative adversarial network (GAN) model to produce realistic attributes, learned from an existing real-world dataset. G2A2 is scalable and can generate a graph with a million edges in under a minute of computing time.

This repository contains code for G2A2 and a realistic graph library containing G2A2-generated social media graphs, article graphs, and Internet traffic graphs. The library
encompasses graphs with varying anomaly percentages, as well as different numbers of nodes and edges, providing researchers with a tool for benchmarking various algorithms.

##Citation

[Pending] Will be provided as soon as the proceedings of 21st ACM International Conference on Computing Frontiers (CF' 24) is released.
