---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p>
  I am Jie Sun. I'm working on AI infrastructure at Bytedance. I got my Ph.D. from the Department of Computer Science at Zhejiang University, under the supervision of Zeke Wang and Fei Wu. My research focuses on the intersection of AI algorithms and AI infrastructure. I have previously worked on building efficient and scalable systems for GNN, DLRM, and LLM, utilizing heterogeneous hardware such as NVMe SSDs and GPUs. Currently, I am exploring algorithm-system co-design, with a particular emphasis on pushing the boundaries of large model training, such as scaling large recommendation models. I have been selected for top talent tracks at ByteDance, Alibaba, Tencent, Ant Group, and Huawei.
</p>
<p style="margin: 30px 0;"></p>

Publications
======
<p style="font-size: 16px;">
  <li>
  <b>BAT: Efficient Generative Recommender Serving with Bipartite Attention</b><br>
  <b>Jie Sun</b>, Shaohang Wang, Zimo Zhang, Zhengyu Liu, Yunlong Xu, Peng Sun, Bo Zhao, Bingsheng He, Fei Wu, Zeke Wang<br>
  <i>International Conference on Architectural Support for Programming Languages and Operating Systems (<b>ASPLOS</b>), 2026</i> &nbsp;<em class="blue"></em><br>
  <a href="../files/bat-asplos26-sun.pdf" target="_blank" style="text-decoration: none;">
  [Paper]</a>
  We propose a model-system co-design to accelerate generative recommender serving. The key idea is to selectively use User-as-prefix attention and Item-as-prefix attention to improve KV cache utilization while maintaining accuracy. We have validated the key algorithm with production workloads.
  </li>
</p>

<p style="font-size: 16px;">
  <li>
  <b>Legion: Automatically Pushing the Envelope of Multi-GPU System for Billion-Scale GNN Training</b><br>
  <b>Jie Sun</b>, Li Su, Zuocheng Shi, Wenting Shen, Zeke Wang, Lei Wang, Jie Zhang, Wenyuan Yu, Yong Li, Jingren Zhou, Fei Wu<br>
  <i>USENIX Annual Technical Conference (<b>ATC</b>), 2023</i> &nbsp;<em class="blue"></em><br>
  <a href="https://www.usenix.org/system/files/atc23-sun.pdf" target="_blank" style="text-decoration: none;">[Paper]</a>
  <a href="https://github.com/RC4ML/Legion" target="_blank" style="text-decoration: none;">[Code]</a><br>
  We build Legion with the co-design of GPU-topology-aware hierarchical graph partitioning with NVLink-enhanced multi-GPU unified cache to accelerate large-scale GNNs training. Legion minimizes CPU-GPU PCIe traffic, achieving throughput close to pure in-GPU systems even with billion-scale graphs.
  </li>
</p>

<p style="font-size: 16px;">
  <li>
  <b>Hyperion: Co-optimizing SSD Access and GPU Computation for Cost-efficient Out-of-core GNN Training</b><br>
  <b>Jie Sun</b>, Mo Sun, Zheng Zhang, Zuocheng Shi, Jun Xie, Zihan Yang, Jie Zhang, Fei Wu, Zeke Wang<br>
  <i>IEEE International Conference on Data Engineering (<b>ICDE</b>), 2025</i><br>
  <a href="../files/Hyperion_ICDE_25_final.pdf" target="_blank" style="text-decoration: none;">[Paper]</a>
  <a href="https://github.com/RC4ML/Hyperion" target="_blank" style="text-decoration: none;">[Code]</a><br>
  We build Hyperion, a cost-efficient out-of-core GNN training system that can achieve in-memory-like throughput on terabyte-scale graphs with some cheap NVMe SSDs. We also propose a GPU-initiated asynchronous disk IO stack to saturate SSDs with only a few GPU cores. We believe the asynchronous disk IO stack can be further applied to other out-of-core applications like DLRM, LLM inference (KVCache in disk), and RAG systems.
  </li>
</p>


<p style="font-size: 16px;">
  <li>
  <b>Helios: Efficient Distributed Dynamic Graph Sampling for Online GNN Inference</b><br>
  <b>Jie Sun</b><sup>*</sup>, Zuocheng Shi<sup>*</sup>, Li Su, Wenting Shen, Zeke Wang, Yong Li, Wenyuan Yu, Wei Lin, Fei Wu, Bingsheng He, Jingren Zhou. <sup>*</sup>: Contributed equally to this project.<br>
  <i>Annual Symposium on Principles and Practice of Parallel Programming (<b>PPoPP</b>), 2025</i><br>
  <a href="../files/ppopp25-final32.pdf" target="_blank" style="text-decoration: none;">[Paper]</a>
  <a href="https://github.com/alibaba/graph-learn" target="_blank" style="text-decoration: none;">[Code]</a><br>
  We build Helios, a distributed dynamic graph sampling service for online GNN inference. Helios can achieve millisecond-level sampling latency on rapidly updated dynamic graphs and can linearly scale out. Helios is now part of Alibaba Graph-Learn, an industrial GNN framework. See dynamic sampling services for more details (https://graph-learn.readthedocs.io/en/latest/en/dgs/intro.html).
  </li>
</p>

<p style="font-size: 16px;">
  <li>
  <b>Moment: Co-optimizing Physical 
Communication Topology and Data Placement for Multi-GPU Out-of-core GNN Training. </b><br>
  Zuocheng Shi<sup>*</sup>, <b>Jie Sun</b><sup>*</sup>, Ziyu Song, Mo Sun, Yang Xiao, Fei Wu, Bingsheng He, Zeke Wang. <sup>*</sup>: Contributed equally to this project.<br>
  <i>International Conference for High Performance Computing, Networking, Storage, and Analysis (<b>SC, Best Student Paper Finalist</b>), 2025</i><br>
  <a href="../files/Moment_ Co-optimizing Physical Communication Topology and Data Placement for Multi-GPU Out-of-core GNN Training.pdf" target="_blank" style="text-decoration: none;">[Paper]</a>
  We propose Moment, a physical communication topology and data placement co-optimizer to enable high-throughput and low-cost GNN training in a multi-GPU machine. Moment addresses communication contention and GPU load imbalance issues by modeling the physical topology as capacity-constrained directed graphs and formulating communication scheduling as a max-flow problem. It also introduces a data-distribution-aware knapsack algorithm for optimized data placement.
  </li>
</p>

<p style="font-size: 16px;">
  <li>
  <b>TorchGT: A Holistic System for Large-scale Graph Transformer Training</b><br>
  Meng Zhang<sup>*</sup>,  <b>Jie Sun</b><sup>*</sup>, Qinghao Hu, Peng Sun, Zeke Wang, Yonggang Wen, Tianwei Zhang.  <sup>*</sup>: Contributed equally to this project.<br>
  <i>International Conference for High Performance Computing, Networking, Storage, and Analysis (<b>SC</b>), 2024</i><br>
  <a href="https://arxiv.org/pdf/2407.14106" target="_blank" style="text-decoration: none;">[Paper]</a>
  Graph transformers achieve higher capabilities to capture global/long-range effects than GNNs. However, the quadratic computation cost of self-attention makes it hard to scale. We propose TorchGT with algorithm and system co-design to accelerate Graph Transformer training and scale up to over 1M sequence length.
  </li>
</p>

<p style="font-size: 16px;">
  <li>
  <b>SSiMD: Supporting Six Signed Multiplications in a DSP Block for Low-Precision CNN on FPGAs</b><br>
  Qi Liu, Mo Sun, <b>Jie Sun</b>, Liqiang Lu, Jieru Zhao, Zeke Wang<br>
  <i>International Conference on Field-Programmable Technology (<b>FPT</b>), 2023</i> <br>
  </li>
</p>

<p style="font-size: 16px;">
  <li>
  <b>SparseACC: A Generalized Linear Model Accelerator for Sparse Datasets</b><br>
  Jie Zhang, Hongjing Huang, <b>Jie Sun</b>, Juan G ́omez Luna, Onur Mutlu, Zeke Wang<br>
  <i>IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (<b>TCAD</b>), 2023</i><br>
  </li>
</p>

<p style="font-size: 16px;">
  <li>
  <b>P4SGD: Programmable Switch Enhanced Model-Parallel Training on Generalized Linear Models on Distributed FPGAs</b><br>
  Hongjing Huang, Yingtao Li, <b>Jie Sun</b>, Xueying Zhu, Jie Zhang, Liang Luo, Jialin Li, Zeke Wang<br>
  <i>IEEE Transactions Parallel and Distributed System (<b>TPDS</b>), 2023</i><br>
  </li>
</p>
<p style="margin: -10px 0;"></p>

<p style="font-size: 16px;">
  <li>
  <b>FlashANNS: GPU-Driven Asynchronous I/O Pipelining for Eliminating Storage-Compute Bottlenecks in Billion-Scale Similarity Search</b><br>
  Yang Xiao, Mo Sun, Ziyu Song, Bing Tian, <b>Jie Sun</b>, Jie Zhang, Zeke Wang, Zonghui Wang, Wenzhi Chen, Fei Wu<br>
  <i> ACM Special Interest Group on Management of Data (<b>SIGMOD</b>), 2026</i><br>
  </li>
  To appear.
</p>
<p style="margin: -10px 0;"></p>

Education
======
<p style="font-size: 16px;">
  [Sep. 2021 - Jun. 2026] Zhejiang University, Ph.D. in Computer Science (CS)<br>
  [Sep. 2017 – Jun. 2021] Zhejiang University, B.S. in Electronic Engineering (EE)<br>
</p>

Internship
======
<p style="font-size: 16px;">
  [July 2025 -- March 2026] Research Intern, Taobao & Tmall Group of Alibaba, Focus on Generative Recommender System<br>
  [June 2024 -- July 2025] Research Intern, NUS Xtra Group, supervised by Bingsheng He<br>
  [Nov 2020 - June 2024] Research Intern, Tongyi Lab of Alibaba Group<br>
</p>

Awards
======
<p style="font-size: 16px;">
  [June. 2025] SC 25 Best Student Paper Finalist<br>
  [Jan. 2024] Alibaba Outstanding Research Intern (by Tongyi Lab)<br>
  [Jan. 2023] Eurosys 23 Best Poster Award, for the early work of Helios<br>
  [June. 2023] Outstanding Graduate Student of Zhejiang University<br>
  [Jan. 2021] Alibaba-Zhejiang University Joint Institute of Frontier Technologies（AZFT）Annual Outstanding Research Intern<br>
</p>

Services
======
<p style="font-size: 16px;">
  Reviewer of TC,WSDM <br>
</p>

