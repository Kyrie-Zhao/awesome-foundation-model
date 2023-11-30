# Awesome Foundation Model ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) [![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)] 

This is a list of awesome _**Foundation Model for X and X for Foundation Model**_ related projects & papers. 

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

## Contents
- [Benchmark and Dataset](#benchmark-and-dataset)
- [Open Source Projects](#open-source-projects)
- [Papers](#papers)
  - [Multi Modal](#multi-modal)
  - [Efficient Inference](#efficient-inference)
  - [Efficient Training](#efficient-training)
  - [Optimization](#optimization)
  - [Healthcare](#healthcare)
  - [Code Optimization and Compiler](#code-optimization-and-compiler)
  - [Data Selection](#data-selection)
  - [Others](#others)

## Benchmark and Dataset
- [Embedchain](https://github.com/embedchain/embedchain)
  
## Open Source Projects
- [ImageBind](https://github.com/facebookresearch/ImageBind)
- [MetaTransformer](https://github.com/invictus717/MetaTransformer)

## Papers

### Multi Modal
- [ImageBind: One embedding space to bind them all](https://openaccess.thecvf.com/content/CVPR2023/papers/Girdhar_ImageBind_One_Embedding_Space_To_Bind_Them_All_CVPR_2023_paper.pdf) by Girdhar, Rohit, et al., CVPR 2023
- [LM-Nav: Robotic Navigation with Large Pre-Trained Models of Language, Vision, and Action](https://arxiv.org/pdf/2207.04429.pdf) by Shah, Dhruv, Błażej Osiński, and Sergey Levine., PMLR 2023

### Efficient Inference 
- [FlexGen: High-throughput Generative Inference of Large Language Models with a Single GPU](https://arxiv.org/pdf/2303.06865) by Sheng, Ying, et al., ICML 2023
- [Tabi: An Efficient Multi-Level Inference System for Large Language Models](https://dl.acm.org/doi/pdf/10.1145/3552326.3587438?casa_token=2Ju1tOw9-OQAAAAA:JiW7lFRbuCbNQp8JxLKq0_Fu5O2HnPKnCtXSBuWYiW0HOJa5AhUEhvaAQVBVoyDN0qAgI2abM73h20A) by Wang, Yiding, et al. EuroSys 2023
- [EFFICIENTLY SCALING TRANSFORMER INFERENCE](https://arxiv.org/pdf/2211.05102) by Pope, Reiner, et al., arxiv 2022
- [SpecInfer: Accelerating Generative LLM Serving with Speculative Inference and Token Tree Verification](https://arxiv.org/pdf/2305.09781) by Miao, Xupeng, et al., arxiv 2023
- [EnergonAI: An Inference System for 10-100 Billion Parameter Transformer Models](https://arxiv.org/pdf/2209.02341) by Du, Jiangsu, et al., arxiv 2022
- [AlpaServe: Statistical Multiplexing with Model Parallelism for Deep Learning Serving](https://arxiv.org/pdf/2302.11665) by Li, Zhuohan, et al., OSDI 2023
- [STI: Turbocharge NLP Inference at the Edge via Elastic Pipelining](https://dl.acm.org/doi/pdf/10.1145/3575693.3575698) by Guo, Liwei, Wonkyo Choe, and Felix Xiaozhu Lin., ASPLOS 2023
- [DeepSpeed-inference: enabling efficient inference of transformer models at unprecedented scale](https://ieeexplore.ieee.org/iel7/10046045/10045783/10046087.pdf?casa_token=-l-VUdoAL9cAAAAA:Zt9pbjDGwTuqtX-RSm6Np74l4mUYuPp6ls_xH-wdaIPQig-A6UduT7xDn8Wcsv05W1imTH08mhU) by Aminabadi, Reza Yazdani, et al., SC 2022
- [PETALS: Collaborative Inference and Fine-tuning of Large Models](https://arxiv.org/pdf/2209.01188) by Borzunov, Alexander, et al., arxiv 2022
- 
- [Fast Distributed Inference Serving for Large Language Models](https://arxiv.org/pdf/2305.05920) by Wu, Bingyang, et al., arxiv 2023
- [DISTRIBUTED INFERENCE AND FINE-TUNING OF LARGE LANGUAGE MODELS OVER THE INTERNET](https://openreview.net/pdf?id=HLQyRgRnoXo) under review
- [Orca: A Distributed Serving System for {Transformer-Based} Generative Models](https://www.usenix.org/system/files/osdi22-yu.pdf) by Yu, Gyeong-In, et al., OSDI 2022

### Efficient Training
- [TopoopT: Co-optimizing Network Topology and Parallelization Strategy for Distributed Training Jobs](https://www.usenix.org/system/files/nsdi23-wang-weiyang.pdf) by Wang, Weiyang, et al., NSDI 2023
- [Breadth-First Pipeline Parallelism](https://arxiv.org/pdf/2211.05953) by Lamy-Poirier, Joel., MLSys 2023
- [On Optimizing the Communication of Model Parallelism](https://arxiv.org/pdf/2211.05322.pdf) by Zhuang, Yonghao, et al., MLSys 2023
- [Galvatron: Efficient Transformer Training over Multiple GPUs Using Automatic Parallelism](https://arxiv.org/pdf/2211.13878) by Miao, Xupeng, et al., arxiv 2022
- [Overlap Communication with Dependent Computation via Decomposition in Large Deep Learning Models](https://dl.acm.org/doi/pdf/10.1145/3567955.3567959) by Wang, Shibo, et al., ASPLOS 2023
  
### Optimization 
- [Vcc: Scaling Transformers to 128K Tokens or More by Prioritizing Important Tokens](https://arxiv.org/pdf/2305.04241) by Zeng, Zhanpeng, et al., arxiv 2023

### Healthcare
- [Multimodal LLMs for health grounded in individual-specific data](https://arxiv.org/pdf/2307.09018) by Belyaeva, Anastasiya, et al., arxiv 2023
- [Path to Medical AGI: Unify Domain-specific Medical LLMs with the Lowest Cost](https://arxiv.org/pdf/2306.10765) by Zhou, Juexiao, Xiuying Chen, and Xin Gao., arxiv 2023
- [Decoding speech perception from non-invasive brain recordings](https://www.nature.com/articles/s42256-023-00714-5) by Défossez, Alexandre, et al., Nature Machine Intelligence 2023
- [Large language models improve Alzheimer’s disease diagnosis using multi-modality data](https://arxiv.org/pdf/2305.19280) by Feng, Yingjie, et al., arxiv 2023
- [Neuro-GPT: Developing A Foundation Model for EEG](https://arxiv.org/pdf/2311.03764) by Cui, Wenhui, et al., arxiv 2023
- [From Classification to Clinical Insights: Towards Analyzing and Reasoning About Mobile and Behavioral Health Data With Large Language Models](https://arxiv.org/pdf/2311.13063) by Englhardt, Zachary, et al., arxiv 2023

### Code Optimization and Compiler
- [Can Large Language Models Reason about Program Invariants?](https://openreview.net/pdf?id=mXv2aVqUGG) by Pei, Kexin, et al., ICML 2023
- [The Hitchhiker's Guide to Program Analysis: A Journey with Large Language Models](https://arxiv.org/pdf/2308.00245) by Li, Haonan, et al., arxiv 2023
- [Clover: Closed-Loop Verifiable Code Generation](https://arxiv.org/pdf/2310.17807) by Sun, Chuyue, et al., arxiv 2023
- [Formalizing Natural Language Intent into Program Specifications via Large Language Models](https://arxiv.org/pdf/2310.01831) by Endres, Madeline, et al., arxiv 2023
- [Ranking LLM-Generated Loop Invariants for Program Verification](https://arxiv.org/pdf/2310.09342) by Chakraborty, Saikat, et al., arxiv 2023
- [Large language models for compiler optimization](https://arxiv.org/pdf/2309.07062) by Cummins, Chris, et al., arxiv 2023

### Others
- [ClimaX: A foundation model for weather and climate](https://arxiv.org/pdf/2301.10343) by Nguyen, Tung, et al., arxiv 2023

### Data Selection
- [Towards Free Data Selection with General-Purpose Models](https://arxiv.org/pdf/2309.17342) by Xie, Yichen, et al., arxiv 2023



