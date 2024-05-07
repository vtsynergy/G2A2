# G2A2: Graph Generator with Attributes and Anomalies

G2A2 is an automated <ins>g</ins>raph <ins>g</ins>enerator with <ins>a</ins>ttributes and <ins>a</ins>nomalies. It is a highly accurate, flexible, and scalable graph generator that can generate graphs with ground truth.

This repository contains code for G2A2 and a realistic graph library containing G2A2-generated social media graphs, article graphs, and Internet traffic graphs. The library
encompasses graphs with varying anomaly percentages, as well as different numbers of nodes and edges, providing researchers with a tool for benchmarking various algorithms.

| Domain                 | #nodes (U) | #nodes (V) | #edges  | anomaly% | Features | Avg. Degree | Avg. BCC (U) | Avg. BCC (V) | Duration (hrs) | Link |
|------------------------|------------|------------|---------|----------|----------|-------------|--------------|--------------|----------------|------|
| G2A2-Social Media      | 100000     | 10000      | 1000000 | 1        | 172      |             |              |              | 744            |      |
| G2A2-Social Media      | 100000     | 10000      | 1000000 | 5        | 172      |             |              |              | 744            |      |
| G2A2-Social Media      | 100000     | 10000      | 1000000 | 10       | 172      |             |              |              | 744            |      |
| G2A2-Computer Networks | 100000     | 10000      | 1000000 | 1        | 19       |             |              |              | 144            |      |
| G2A2-Computer Networks | 100000     | 10000      | 1000000 | 5        | 19       |             |              |              | 144            |      |
| G2A2-Computer Networks | 100000     | 10000      | 1000000 | 10       | 19       |             |              |              | 144            |      |

### Citation

[Pending] Will be provided as soon as the proceedings of 21st ACM International Conference on Computing Frontiers (CF' 24) is released.
