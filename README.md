## awesome-graph-transformer

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
<!--![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/ChandlerBang/awesome-self-supervised-gnn?color=yellow)  ![Forks](https://img.shields.io/github/forks/ChandlerBang/awesome-self-supervised-gnn?color=blue&label=Fork) -->

This repository contains a list of papers on the Graph Transformers; we categorize them based on their detailed techniques.

We will try to make this list updated. If you found any error or any missed paper, please don't hesitate to open an issue or pull request.

### Structural Encoding / Postional Encoding for Graph Transformers
#### Spectral Positional Encoding
1. Rethinking Graph Transformers with Spectral Attention. NeurIPS 2021. [[paper]](https://arxiv.org/abs/2106.03893)
1. A Generalization of Transformer Networks to Graphs. AAAI workshop 2021. [[paper]](https://arxiv.org/pdf/2012.09699)

#### Other Structure-aware Encoding
1. Do Transformers Really Perform Bad for Graph Representation? NeurIPS 2021. [[paper]](https://arxiv.org/abs/2106.05234)
1. Graph Neural Networks with Learnable Structural and Positional Representations. ICLR 2022. [[paper]](https://arxiv.org/abs/2110.07875)
1. GRPE: Relative Positional Encoding for Graph Transformer. ICLR 2022 Workshop MLDD [[paper]](https://openreview.net/forum?id=GNfAFN_p1d)
1. Global Self-Attention as a Replacement for Graph Convolution. KDD 2022. [[paper]](https://arxiv.org/abs/2108.03348)
1. Pure Transformers are Powerful Graph Learners. NeurIPS 2022. [[paper]](https://arxiv.org/abs/2207.02505)
1. Are More Layers Beneficial to Graph Transformers? ICLR 2023. [[paper]](https://openreview.net/forum?id=uagC-X9XMi8)

#### Graph Neural Network as Structural Encoder
1. GraphiT: Encoding Graph Structure in Transformers. Arxiv 2021. [[paper]](https://arxiv.org/abs/2106.05667)
1. Representing Long-Range Context for Graph Neural Networks with Global Attention. NeurIPS 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/6e67691b60ed3e4a55935261314dd534-Paper.pdf)
1. Structure-Aware Transformer for Graph Representation Learning. ICML 2022. [[paper]](https://proceedings.mlr.press/v162/chen22r.html)
1. Recipe for a General, Powerful, Scalable Graph Transformer. NeurIPS 2022. [[paper]](https://arxiv.org/abs/2205.12454)

### Scalability of Graph Transformers (Graph Transformers on Large Graphs)
#### Transformers with Sampling
1. A Self-Attention Network based Node Embedding Model. ECML-PKDD 2020. [[paper]](https://arxiv.org/abs/2006.12100)
1. Heterogeneous Graph Transformer. WWW 2020. [[paper]](https://arxiv.org/abs/2003.01332)
1. Gophormer: Ego-Graph Transformer for Node Classification. Arxiv 2021. [[paper]](https://arxiv.org/abs/2110.13094)
1. Coarformer: Transformer for large graph via graph coarsening. Openreview 2021. [[paper]](https://openreview.net/forum?id=fkjO_FKVzw)
1. Hierarchical Graph Transformer with Adaptive Node Sampling. NeurIPS 2022. [[paper]](https://arxiv.org/abs/2210.03930)
1. NAGphormer: A Tokenized Graph Transformer for Node Classification in Large Graphs. ICLR 2023. [[paper]](https://openreview.net/forum?id=8KYeilT3Ow)

#### Transformers with Adapted Attention
1. From block-Toeplitz matrices to differential equations on graphs: towards a general theory for scalable masked Transformers. ICML 2022. [[paper]](https://arxiv.org/abs/2107.07999)
1. Recipe for a General, Powerful, Scalable Graph Transformer. NeurIPS 2022. [[paper]](https://arxiv.org/abs/2205.12454)
1. Deformable Graph Transformer. Arxiv 2022. [[paper]](https://arxiv.org/abs/2206.14337)
1. NodeFormer: A Scalable Graph Structure Learning Transformer for Node Classification. NeurIPS 2022. [[paper]](https://openreview.net/forum?id=sMezXGG5So)
1. DIFFormer: Scalable (Graph) Transformers Induced by Energy Constrained Diffusion. ICLR 2023. [[paper]](https://arxiv.org/abs/2301.09474)

### Applications of Graph Transformers (Molecules, Texts, Knowledge Graphs)
1. Modeling Graph Structure in Transformer for Better AMR-to-Text Generation. EMNLP 2019. [[paper]](https://aclanthology.org/D19-1548/)
1. Heterogeneous Graph Transformer for Graph-to-Sequence Learning. ACL 2020. [[paper]](https://aclanthology.org/2020.acl-main.640/)
1. Molecule Attention Transformer. Arxiv 2020. [[paper]](https://arxiv.org/abs/2002.08264)
1. Interpretable Rumor Detection in Microblogs by Attending to User Interactions. AAAI 2020. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6405)
1. Graph Transformer for Graph-to-Sequence Learning. AAAI 2020. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6243)
1. Self-Supervised Graph Transformer on Large-Scale Molecular Data. NeurIPS 2020. [[paper]](https://proceedings.neurips.cc/paper/2020/hash/94aef38441efa3380a3bed3faf1f9d5d-Abstract.html)
1. SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks. NeurIPS 2020. [[paper]](https://proceedings.neurips.cc/paper/2020/hash/15231a7ce4ba789d13b722cc5c955834-Abstract.html)
1. Modeling Graph Structure via Relative Position for Text Generation from Knowledge Graphs. TextGraphs 2021. [[paper]](https://arxiv.org/abs/2006.09242)
1. GraphFormers: GNN-nested Transformers for Representation Learning on Textual Graph. NeurIPS 2021. [[paper]](https://arxiv.org/pdf/2105.02605.pdf)
1. Systematic Generalization with Edge Transformers. NeurIPS 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/0a4dc6dae338c9cb08947c07581f77a2-Paper.pdf)
1. Mesh Graphormer. ICCV 2021. [[paper]](https://openaccess.thecvf.com/content/ICCV2021/html/Lin_Mesh_Graphormer_ICCV_2021_paper.html)
1. Relative Molecule Self-Attention Transformer. Arxiv 2021. [[paper]](https://arxiv.org/abs/2110.05841)
1. Neighbour Interaction based Click-Through Rate Prediction via Graph-masked Transformer. Arxiv 2022. [[paper]](https://arxiv.org/abs/2201.13311)
1. Equivariant Transformers for Neural Network based Molecular Potentials. ICLR 2022. [[paper]](https://openreview.net/forum?id=zNHzqZ9wrRB)
1. Periodic Graph Transformers for Crystal Material Property Prediction. NeurIPS 2022. [[pper]](https://arxiv.org/abs/2209.11807)
1. Brain Network Transformer. NeurIPS 2022. [[paper]](https://openreview.net/forum?id=1cJ1cbA6NLN)
1. Multi-Relational Graph Transformer for Automatic Short Answer Grading. NAACL-HLT 2022. [[paper]](https://aclanthology.org/2022.naacl-main.146.pdf)
1. Mask and Reason: Pre-Training Knowledge Graph Transformers for Complex Logical Queries. KDD 2022. [[paper]](https://dl.acm.org/doi/10.1145/3534678.3539472)
1. Relphormer: Relational Graph Transformer for Knowledge Graph Representations. Arxiv 2022. [[paper]](https://arxiv.org/abs/2205.10852)
1. CoAtGIN: Marrying Convolution and Attention for Graph-based Molecule Property Prediction. BIBM 2022. [[paper]](https://ieeexplore.ieee.org/abstract/document/9995324)
1. DiGress: Discrete Denoising diffusion for graph generation. ICLR 2023. [[paper]](https://arxiv.org/abs/2209.14734)

### Pre-training with Graph Transformers
1. Selfsupervised graph transformer on large-scale molecular data. NeurIPS 2020. [[paper]](https://arxiv.org/abs/2007.02835)
1. Graph-Bert: Only Attention is Needed for Learning Graph Representations. Arxiv 2020. [[paper]](https://arxiv.org/abs/2001.05140)
1. Graph Masked Autoencoders with Transformers. Arxiv 2022. [[paper]](https://arxiv.org/abs/2202.08391)

### Survey
1. Transformer for Graphs: An Overview from Architecture Perspective. Arxiv 2022. [[paper]](https://arxiv.org/abs/2202.08455)
1. A Survey on Graph Neural Networks and Graph Transformers in Computer Vision: A Task-Oriented Perspective. Arxiv 2022. [[paper]](https://arxiv.org/abs/2209.13232)
1. Attending to Graph Transformers. Arxiv 2022. [[paper]](https://arxiv.org/abs/2302.04181)

### Neural Architecture Search (NAS) for Graph Transformers
1. AutoGT: Automated Graph Transformer Architecture Search. ICLR 2023. [[paper]](https://openreview.net/forum?id=GcM7qfl5zY)

### Uncategorized
1. Transformers Generalize DeepSets and Can be Extended to Graphs & Hypergraphs. NeurIPS 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/ec0f40c389aeef789ce03eb814facc6c-Paper.pdf)
1. Universal Graph Transformer Self-Attention Networks. WWW 2022. [[paper]](https://dl.acm.org/doi/abs/10.1145/3487553.3524258)
1. Masked Label Prediction: Unified Message Passing Model for Semi-Supervised Classification. IJCAI 2021. [[paper]](https://www.ijcai.org/proceedings/2021/0214)
1. Long Range Graph Benchmark. NeurIPS 2022. [[paper]](https://openreview.net/forum?id=in7XC5RcjEn)
1. Rethinking the Expressive Power of GNNs via Graph Biconnectivity. ICLR 2023. [[paper]](https://openreview.net/forum?id=r9hNv76KoT3)
1. Relational Attention: Generalizing Transformers for Graph-Structured Tasks. ICLR 2023. [[paper]](https://openreview.net/forum?id=cFuMmbWiN6)
