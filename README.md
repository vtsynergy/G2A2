# G2A2: Graph Generator with Attributes and Anomalies

G2A2 is an automated <ins>g</ins>raph <ins>g</ins>enerator with <ins>a</ins>ttributes and <ins>a</ins>nomalies. It is a highly accurate, flexible, and scalable graph generator that can generate graphs with ground truth.

This repository contains code for G2A2 and a realistic graph library containing G2A2-generated social media graphs, article graphs, and Internet traffic graphs. The library
encompasses graphs with varying anomaly percentages, as well as different numbers of nodes and edges, providing researchers with a tool for benchmarking various algorithms.

| Domain                 | #nodes (U) | #nodes (V) | #edges  | anomaly% | Features | Duration (hrs) | Link |
|------------------------|------------|------------|---------|----------|----------|----------------|------|
| G2A2-Social Media      | 100000     | 10000      | 1000000 | 1        | 172      | 744            | [Download](https://drive.google.com/file/d/12zHuJO4fMHQ42Qa6X9fb-Dwc3F2yr64w/view?usp=sharing)      |
| G2A2-Social Media      | 100000     | 10000      | 1000000 | 5        | 172      | 744            | [Download](https://drive.google.com/file/d/1sHtXTRmcry1F4BuVnbGvoDR_aW1mz9pr/view?usp=sharing)     |
| G2A2-Social Media      | 100000     | 10000      | 1000000 | 10       | 172      | 744            | [Download](https://drive.google.com/file/d/1ru8J3mhfuqj3-y_z0FcfKRR78WC4s1Nw/view?usp=sharing)     |
| G2A2-Computer Networks | 100000     | 10000      | 1000000 | 1        | 19       | 144            |  [Download](https://drive.google.com/file/d/1Zr7GjSvtx3_KsOaQRksMXmf3eo_Fo-2W/view?usp=sharing)    |
| G2A2-Computer Networks | 100000     | 10000      | 1000000 | 5        | 19       | 144            |  [Download](https://drive.google.com/file/d/18pQZtR9OVMEUZ7x4WanD27x16AE1ztd9/view?usp=sharing)    |
| G2A2-Computer Networks | 100000     | 10000      | 1000000 | 10       | 19       | 144            |  [Download](https://drive.google.com/file/d/1j2RVDRcokvQP3-F1zOR4P_LnsrNVFFdw/view?usp=sharing)   |

# Citation
If you use this code, please cite our Computing Frontiers (CF'24) paper:
```
@inproceedings{10.1145/3649153.3649206,
author = {Dey, Saikat and Jha, Sonal and Feng, Wu-chun},
title = {G2A2: Graph Generator with Attributes and Anomalies},
year = {2024},
isbn = {9798400705977},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3649153.3649206},
doi = {10.1145/3649153.3649206},
booktitle = {Proceedings of the 21st ACM International Conference on Computing Frontiers},
pages = {3–11},
numpages = {9},
keywords = {Graph generation, bipartite graphs, dynamic graphs, ground truth},
location = {Ischia, Italy},
series = {CF '24}
}
```

# License

&copy; Virginia Polytechnic Institute and State University, 2023.

Please refer to the included [LICENSE](./LICENSE) file.
