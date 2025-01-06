---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, I'm Jie Sun. I am a fourth-year Ph.D. student in the Department of Computer Science at Zhejiang University, supervised by Zeke Wang and Fei Wu. My areas of interest include machine learning systems, graph computing, and recommendation systems. 

Publications
======
- **USENIX ATC 2023: Legion: Automatically Pushing the Envelope of Multi-GPU System for Billion-Scale GNN Training**
[[paper]](https://www.usenix.org/system/files/atc23-sun.pdf)[[code]](https://github.com/RC4ML/Legion)

  **Jie Sun**, Li Su, Zuocheng Shi, Wenting Shen, Zeke Wang, Lei Wang, Jie Zhang, Wenyuan Yu, Yong Li, Jingren Zhou, Fei Wu
  
  We build Legion with the co-design of GPU-topology-aware hierarchical graph partitioning with NVLink-enhanced multi-GPU unified cache to accelerate large-scale GNNs training. Legion minimizes CPU-GPU PCIe traffic, achieving throughput close to pure in-GPU systems even with billion-scale graphs.
  
- **ICDE 2025: Hyperion: Optimizing SSD Access is All You Need to Enable Cost-efficient Out-of-core GNN Training**
[[paper]](https://arxiv.org/pdf/2310.00837v1)[[code]](https://github.com/RC4ML/Hyperion)

  **Jie Sun**, Mo Sun, Zheng Zhang, Zuocheng Shi, Jun Xie, Zihan Yang, Jie Zhang, Fei Wu, Zeke Wang
  
  We build Hyperion, a cost-efficient out-of-core GNN training system that can achieve in-memory-like throughput on terabyte-scale graphs with some cheap NVMe SSDs. We also propose a GPU-initiated asynchronous disk IO stack to saturate SSDs with only a few GPU cores. We believe the asynchronous disk IO stack can be further applied to other out-of-core applications like DLRM, LLM inference (KVCache in disk), and RAG systems.
  
- **PPoPP 2025: Helios: Efficient Distributed Dynamic Graph Sampling for Online GNN Inference**
[[paper]](coming soon)[[code]](https://github.com/alibaba/graph-learn)

  **Jie Sun**, Zuocheng Shi, Li Su, Wenting Shen, Zeke Wang, Yong Li, Wenyuan Yu, Wei Lin, Jingren Zhou, Fei Wu, Bingsheng He

  We build Helios, a distributed dynamic graph sampling service for online GNN inference. Helios can achieve millisecond-level sampling latency on rapidly updated dynamic graphs and can linearly scale out. Helios is now part of Alibaba Graph-Learn, an industrial GNN framework. See dynamic sampling services for more details (https://graph-learn.readthedocs.io/en/latest/en/dgs/intro.html).
  
- **SC 2024: TorchGT: A Holistic System for Large-scale Graph Transformer Training**
[[paper]](https://arxiv.org/pdf/2407.14106)

  Meng Zhang^, **Jie Sun^**, Qinghao Hu, Peng Sun, Zeke Wang, Yonggang Wen, Tianwei Zhang.  ^: Contributed equally to this project.
  
  A step forward from GNN systems. Graph transformers achieve higher capabilities to capture global/long-range effects than GNNs. However, the quadratic computation cost of self-attention makes it hard to scale. We propose TorchGT with algorithm and system co-design to accelerate Graph Transformer training and scale up to over 1M sequence length.

- **FPT 2023: SSiMD: Supporting Six Signed Multiplications in a DSP Block for Low-Precision CNN on FPGAs**

  Qi Liu, Mo Sun, **Jie Sun**, Liqiang Lu, Jieru Zhao, Zeke Wang
  
- **TCAD 2023: SparseACC: A Generalized Linear Model Accelerator for Sparse Datasets**
  
  Jie Zhang, Hongjing Huang, **Jie Sun**, Juan G ́omez Luna, Onur Mutlu, Zeke Wang
  
- **TPDS 2023: P4SGD: Programmable Switch Enhanced Model-Parallel Training on Generalized Linear Models on Distributed FPGAs**

   Hongjing Huang, Yingtao Li, **Jie Sun**, Xueying Zhu, Jie Zhang, Liang Luo, Jialin Li, Zeke Wang
  

Education
======
- [Sep. 2021 - Present] Zhejiang University, Ph.D student in Computer Science (CS)
- [Sep. 2017 – Jun. 2021] Zhejiang University, B.S. in Electronic Engineering (EE)

Internship
======
- [June 2024 -- Present] Research Intern, NUS Xtra Group, supervised by Bingsheng He
- [Nov 2020 - June 2024] Research Intern, Alibaba Group

Awards
======
- [Jan. 2014] Alibaba Outstanding Research Intern (by Tongyi Lab)
- [Jan. 2023] Eurosys Best Poster Award, for the early work of Helios
- [June. 2023] Outstanding Graduate Student of Zhejiang University
- [Jan. 2021] Alibaba-Zhejiang University Joint Institute of Frontier Technologies（AZFT）Annual Outstanding Research Intern
