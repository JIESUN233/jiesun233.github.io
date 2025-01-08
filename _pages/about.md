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
  Hello, I'm Jie Sun. I am a fourth-year Ph.D. student in the Department of Computer Science at Zhejiang University, supervised by Zeke Wang and Fei Wu. My areas of interest include machine learning systems, graph computing, and recommendation systems. I like building efficient and scalable machine learning systems (for GNN, DLRM, and LLM) that leverage heterogeneous hardware, such as NVMe SSDs and GPUs, to address large-scale challenges coming from the industry. Currently, I am collaborating with Alibaba on developing a large-scale recommendation system, which is expected to be released in the coming months.
</p>
<p style="margin: 30px 0;"></p>

Publications
======
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
  <b>Hyperion: Optimizing SSD Access is All You Need to Enable Cost-efficient Out-of-core GNN Training</b><br>
  <b>Jie Sun</b>, Mo Sun, Zheng Zhang, Zuocheng Shi, Jun Xie, Zihan Yang, Jie Zhang, Fei Wu, Zeke Wang<br>
  <i>IEEE International Conference on Data Engineering (<b>ICDE</b>), 2025</i><br>
  <a href="https://arxiv.org/pdf/2310.00837v1" target="_blank" style="text-decoration: none;">[Paper]</a>
  <a href="https://github.com/RC4ML/Hyperion" target="_blank" style="text-decoration: none;">[Code]</a><br>
  We build Hyperion, a cost-efficient out-of-core GNN training system that can achieve in-memory-like throughput on terabyte-scale graphs with some cheap NVMe SSDs. We also propose a GPU-initiated asynchronous disk IO stack to saturate SSDs with only a few GPU cores. We believe the asynchronous disk IO stack can be further applied to other out-of-core applications like DLRM, LLM inference (KVCache in disk), and RAG systems.
  </li>
</p>


<p style="font-size: 16px;">
  <li>
  <b>Helios: Efficient Distributed Dynamic Graph Sampling for Online GNN Inference</b><br>
  <b>Jie Sun</b><sup>*</sup>, Zuocheng Shi<sup>*</sup>, Li Su, Wenting Shen, Zeke Wang, Yong Li, Wenyuan Yu, Wei Lin, Fei Wu, Bingsheng He, Jingren Zhou. <sup>*</sup>: Contributed equally to this project.<br>
  <i>Annual Symposium on Principles and Practice of Parallel Programming (<b>PPoPP</b>), 2025</i><br>
  <a href="../files/Helios_PPoPP (32).pdf" target="_blank" style="text-decoration: none;">[Paper]</a>
  <a href="https://github.com/alibaba/graph-learn" target="_blank" style="text-decoration: none;">[Code]</a><br>
  We build Helios, a distributed dynamic graph sampling service for online GNN inference. Helios can achieve millisecond-level sampling latency on rapidly updated dynamic graphs and can linearly scale out. Helios is now part of Alibaba Graph-Learn, an industrial GNN framework. See dynamic sampling services for more details (https://graph-learn.readthedocs.io/en/latest/en/dgs/intro.html).
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

Education
======
<p style="font-size: 16px;">
  [Sep. 2021 - Present] Zhejiang University, Ph.D. student in Computer Science (CS)<br>
  [Sep. 2017 – Jun. 2021] Zhejiang University, B.S. in Electronic Engineering (EE)<br>
</p>

Internship
======
<p style="font-size: 16px;">
  [June 2024 -- Present] Research Intern, NUS Xtra Group, supervised by Bingsheng He<br>
  [Nov 2020 - June 2024] Research Intern, Alibaba Group<br>
</p>

Awards
======
<p style="font-size: 16px;">
  [Jan. 2024] Alibaba Outstanding Research Intern (by Tongyi Lab)<br>
  [Jan. 2023] Eurosys Best Poster Award, for the early work of Helios<br>
  [June. 2023] Outstanding Graduate Student of Zhejiang University<br>
  [Jan. 2021] Alibaba-Zhejiang University Joint Institute of Frontier Technologies（AZFT）Annual Outstanding Research Intern<br>
</p>

