---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from:
  - "/wordpress/"
  - "/wordpress/index.html"
---

{% include base_path %}

I am **Huy Nguyen**, a final-year Ph.D. candidate in [Statistics and Data Science at The University of Texas at Austin](https://stat.utexas.edu/), where I am fortunate enough to be advised by Prof. [Nhat Ho](https://nhatptnk8912.github.io/) and Prof. [Alessandro Rinaldo](https://arinaldo.github.io/). 

My research develops **statistical foundations for modern AI**, with a particular focus on **mixture-of-experts (MoE), multimodal learning, and efficient adaptation of large-scale models**, which is organized around three closely connected themes:

- **Statistical understanding of modern AI architectures.** I study how gating mechanisms, expert structures, and routing rules determine statistical sample complexity and expert specialization in MoE. Beyond MoE, I also investigate the statistical properties of self-attention mechanisms, including how different attention formulations affect sample efficiency.
- **Statistical principles for AI architecture design.** I study how these statistical insights can be translated into architectural principles for modern AI systems. This perspective motivates new designs for sparse MoE, multimodal learning, and attention-based models that aim to improve efficiency, scalability, and specialization.
- **Efficient adaptation of large-scale models.** I investigate how the structure and capacity of lightweight adaptation mechanisms affect the efficiency of adapting large pretrained models. My work focuses on methods such as low-rank adaptation and prompt-based tuning, with an emphasis on their statistical efficiency and principled design.

## Recent News

- **[Sep 2026]** I was selected as a recipient of the Outstanding Graduate Research Fellowship at UT Austin.
- **[Aug 2026]** I will serve as a Senior Program Committee member for AAAI 2027.
- **[Jun 2026]** Our new paper [*On the Geometry of Separation in Finite Gaussian Mixtures*](https://arxiv.org/abs/2606.16179) is available on arXiv.
- **[May 2026]** I was recognized as an ICML 2026 Silver Reviewer.
- **[Jan 2026]** Two papers on prompt-based tuning ([1](https://arxiv.org/pdf/2509.24483), [2](https://arxiv.org/abs/2501.18936)) were accepted to ICLR 2026.
- **[Dec 2025]** Our paper [*Convergence Rates for Softmax Gating Mixture of Experts*](https://ieeexplore.ieee.org/document/11311504) was accepted to *IEEE Transactions on Information Theory*.
- **[Sep 2025]** Our paper [*On Minimax Estimation of Parameters in Softmax-Contaminated Mixture of Experts*](https://arxiv.org/abs/2505.18455) was accepted to NeurIPS 2025.
- **[May 2025]** Two papers on parameter-efficient adaptation ([1](https://arxiv.org/abs/2502.03044), [2](https://arxiv.org/abs/2502.03029)) were accepted to ICML 2025.


## Industrial Experience

- **Morgan Stanley**, Machine Learning Research --- Summer Associate, Summer 2026.
- **Microsoft AI** --- Research Intern, Summer 2024.

## Professional Service

- **Senior Program Committee:** AAAI 2027.
- **Conference Reviewer:** ICML (2022--2026), NeurIPS (2022--2026), AISTATS (2022--2026), ICLR (2024--2027), AAAI (2025--2026).
- **Journal Reviewer:** *Journal of Machine Learning Research (JMLR)*, *Electronic Journal of Statistics (EJS)*, *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, *Transactions on Machine Learning Research (TMLR)*.
- **Seminar Co-organizer:** [StatML@UT](https://sites.google.com/view/statmlut/people?authuser=0), The University of Texas at Austin.

## Books

**[B.1]** [Handbook of Bayesian Deep Learning](https://inria.hal.science/hal-05734505/).  
*BayesAI Consortium*. CRC Press, 2026 (forthcoming).

## Full Publication List by Topics

<details markdown="1">
<summary><strong>Show all publications</strong></summary>

### Theory of Mixture-of-Experts and Related Statistical Models

**[T.20]** [Characterizing Heterogeneous Rates in Finite Mixture Estimation via Partial Optimal Transport
](https://arxiv.org/abs/2609.16622). Under review, 2026 <br/>
*Dung Le\*, __Huy Nguyen\*__, Trang Pham, Alessandro Rinaldo, Nhat Ho*<br/>

**[T.19]** [On the Geometry of Separation in Finite Gaussian Mixtures](https://arxiv.org/abs/2606.16179). Under review, 2026 <br/>
*__Huy Nguyen\*__, Dung Le\*, Alessandro Rinaldo, Nhat Ho*<br/>

**[T.18]** [On DeepSeekMoE: Statistical Benefits of Shared Experts and Normalized Sigmoid Gating](https://arxiv.org/abs/2505.10860). Under review, 2025 <br/>
*__Huy Nguyen__, Thong T. Doan, Quang Pham, Nghi Bui, Nhat Ho\*\*, Alessandro Rinaldo\** *<br/>

**[T.17]** [Convergence Rates for Softmax Gating Mixture of Experts](https://ieeexplore.ieee.org/document/11311504). IEEE Transactions on Information Theory 72(2), 1276-1304, 2026 <br/>
*__Huy Nguyen__, Nhat Ho\*\*, Alessandro Rinaldo\** *<br/>

**[T.16]** [A Statistical Theory of Gated Attention through the Lens of Hierarchical Mixture of Experts](https://arxiv.org/abs/2602.01468). Under review, 2026 <br/>
*Viet Nguyen\*, Tuan Minh Pham\*, Thinh Cao\*, __Huy Nguyen__, Nhat Ho\*\*, Alessandro Rinaldo\** *<br/>

**[T.15]** [Rethinking Multinomial Logistic Mixture of Experts with Sigmoid Gating Function](https://arxiv.org/abs/2602.01466). Under review, 2026 <br/>
*Tuan Minh Pham\*, Thinh Cao\*, Viet Nguyen\*, __Huy Nguyen__, Nhat Ho\*\*, Alessandro Rinaldo\** *<br/>

**[T.14]** [Sigmoid Gating is More Sample Efficient than Softmax Gating in Mixture of Experts](https://arxiv.org/abs/2405.13997). NeurIPS, 2024 <br/>
*__Huy Nguyen__, Nhat Ho\*\*, Alessandro Rinaldo\** *<br/>

**[T.13]** [Sigmoid Self-Attention has Lower Sample Complexity than Softmax Self-Attention: A Mixture-of-Experts Perspective
](https://www.arxiv.org/abs/2502.00281). Under review <br/>
*__Huy Nguyen\*__, Fanqi Yan\*, Pedram Akbarian, Nhat Ho\*\*, Alessandro Rinaldo\** *<br/>

**[T.12]** [Demystifying Softmax Gating Function in Gaussian Mixture of Experts](https://arxiv.org/abs/2305.03288). NeurIPS, 2023  <span style="color:red"> **(Spotlight)** </span> <br/>
*__Huy Nguyen__, TrungTin Nguyen, Nhat Ho*<br/>

**[T.11]** [Is Temperature Sample Efficient for Softmax Gaussian Mixture of Experts?](https://arxiv.org/abs/2401.13875). ICML, 2024 <br/> 
*__Huy Nguyen__, Pedram Akbarian, Nhat Ho*<br/>

**[T.10]** [Statistical Advantages of Perturbing Cosine Router in Mixture of Experts](https://arxiv.org/abs/2405.14131). ICLR, 2025 <br/>
*__Huy Nguyen__, Pedram Akbarian\*, Trang Pham\*, Trang Nguyen\*, Shujian Zhang, Nhat Ho*<br/>

**[T.9]** [Statistical Perspective of Top-K Sparse Softmax Gating Mixture of Experts](https://arxiv.org/abs/2309.13850). ICLR, 2024 <br/>
*__Huy Nguyen__, Pedram Akbarian, Fanqi Yan, Nhat Ho*<br/>

**[T.8]** [On Expert Estimation in Hierarchical Mixture of Experts: Beyond Softmax Gating Functions](https://arxiv.org/abs/2410.02935). Under review <br/>
*__Huy Nguyen\*__, Xing Han\*, Carl William Harris, Suchi Saria\*\*, Nhat Ho\** *<br/>

**[T.7]** [Quadratic Gating Mixture of Experts: Statistical Insights into Self-Attention](https://arxiv.org/abs/2410.11222). Under review <br/>
*Pedram Akbarian\*, __Huy Nguyen\*__, Xing Han\*, Nhat Ho*<br/>

**[T.6]** [A General Theory for Softmax Gating Multinomial Logistic Mixture of Experts](https://arxiv.org/abs/2310.14188). ICML, 2024 <br/>
*__Huy Nguyen__, Pedram Akbarian, TrungTin Nguyen, Nhat Ho*<br/>

**[T.5]** [Towards Convergence Rates for Parameter Estimation in Gaussian-gated Mixture of Experts](https://arxiv.org/abs/2305.07572). AISTATS, 2024 <br/>
*__Huy Nguyen\*__, TrungTin Nguyen\*, Khai Nguyen, Nhat Ho*<br/>

**[T.4]** [Improving Minimax Estimation Rates for Contaminated Mixture of Multinomial Logistic Experts via Expert Heterogeneity](https://arxiv.org/abs/2602.00939). Under review, 2026 <br/>
*Fanqi Yan\*, Dung Le\*, Trang Pham, __Huy Nguyen__, Nhat Ho*<br/>

**[T.3]** [On Minimax Estimation of Parameters in Softmax-Contaminated Mixture of Experts](https://arxiv.org/abs/2505.18455). NeurIPS, 2025 <br/>
*Fanqi Yan\*, __Huy Nguyen\*__, Dung Le\*, Pedram Akbarian, Nhat Ho\*\*, Alessandro Rinaldo\** *<br/>

**[T.2]** [Understanding Expert Structures on Minimax Parameter Estimation in Contaminated Mixture of Experts](https://arxiv.org/abs/2410.12258). AISTATS, 2025 <br/>
*Fanqi Yan\*, __Huy Nguyen\*__, Dung Le\*, Pedram Akbarian, Nhat Ho*<br/>

**[T.1]** [On Parameter Estimation in Deviated Gaussian Mixture of Experts](https://arxiv.org/abs/2402.05220). AISTATS, 2024 <br/>
*__Huy Nguyen__, Khai Nguyen, Nhat Ho*<br/>

### Applications of Mixture-of-Experts

**[A.9]** [FuseMoE: Mixture-of-Experts Transformers for Fleximodal Fusion](https://arxiv.org/abs/2402.03226). NeurIPS, 2024 <br/>
*Xing Han, __Huy Nguyen\*__, Carl Harris\*, Nhat Ho, Suchi Saria*<br/>

**[A.8]** [Mixture of Experts Meets Prompt-Based Continual Learning](https://arxiv.org/abs/2405.14124). NeurIPS, 2024 <br/>
*Minh Le, An Nguyen\*, __Huy Nguyen\*__, Trang Nguyen\*, Trang Pham\*, Linh Van Ngo, Nhat Ho*<br/>

**[A.7]** [Revisiting Prefix-tuning: Statistical Benefits of Reparameterization among Prompts](https://arxiv.org/abs/2410.02200). ICLR, 2025 <br/>
*Minh Le\*, Chau Nguyen\*, __Huy Nguyen\*__, Quyen Tran, Trung Le, Nhat Ho*<br/>

**[A.6]** [Revisit Visual Prompt Tuning: The Expressiveness of Prompt Experts](https://arxiv.org/abs/2501.18936). ICLR, 2026 <br/>
*Minh Le\*, Anh Nguyen\*, __Huy Nguyen__, Chau Nguyen, Nhat Ho*<br/>

**[A.5]** [RepLoRA: Reparameterizing Low-rank Adaptation via the Perspective of Mixture of Experts](https://arxiv.org/abs/2502.03044). ICML, 2025 <br/>
*Tuan Truong\*, Chau Nguyen\*, __Huy Nguyen\*__, Minh Le, Trung Le, Nhat Ho*<br/>

**[A.4]** [On Zero-Initialized Attention: Optimal Prompt and Gating Factor Estimation](https://arxiv.org/abs/2502.03029). ICML, 2025 <br/>
*Nghiem T. Diep\*, __Huy Nguyen\*__, Chau Nguyen\*, Minh Le, Duy M. H. Nguyen, Daniel Sonntag, Mathias Niepert, Nhat Ho*<br/>

**[A.3]** [Learning to Route from Expert Competition: Efficient Training of Sparse Mixture-of-Experts](https://arxiv.org/abs/2505.13380). Under review <br/>
*Nam V. Nguyen, __Huy Nguyen__, Quang Pham, Van Nguyen, Savitha Ramasamy, Nhat Ho*<br/>

**[A.2]** [One-Prompt Strikes Back: Sparse Mixture of Experts for Prompt-based Continual Learning](https://arxiv.org/pdf/2509.24483). ICLR, 2026 <br/>
*Minh Le, Bao-Ngoc Dao, __Huy Nguyen__, Quyen Tran, Anh Nguyen, Nhat Ho*<br/>

**[A.1]** [Hypernetwork-Driven Low-Rank Adaptation Across Attention Heads](http://arxiv.org/abs/2510.04295v2). *Under review* <br/>
*Nghiem T. Diep\*, Dung Le\*, Tuan Truong\*, Tan Dinh, __Huy Nguyen__, Nhat Ho*<br/>

### Optimal Transport

**[O.5]** [Entropic Gromov-Wasserstein between Gaussian Distributions](https://arxiv.org/abs/2108.10961). ICML, 2022 <br/>
*__Huy Nguyen\*__, Khang Le\*, Dung Le\*, Dat Do, Tung Pham, Nhat Ho*<br/>

**[O.4]** [On Multimarginal Partial Optimal Transport: Equivalent Forms and Computational Complexity](https://arxiv.org/abs/2108.07992). AISTATS, 2022 <br/>
*__Huy Nguyen\*__, Khang Le\*, Khai Nguyen, Tung Pham, Nhat Ho*<br/>

**[O.3]** [On Robust Optimal Transport: Computational Complexity and Barycenter Computation](https://arxiv.org/abs/2102.06857). NeurIPS, 2021 <br/>
*__Huy Nguyen\*__, Khang Le\*, Quang Minh Nguyen, Tung Pham, Hung Bui, Nhat Ho*<br/>

**[O.2]** [Fast Approximation of the Generalized Sliced-Wasserstein Distance](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10447733). IEEE ICASSP, 2024 <br/>
*__Huy Nguyen\*__, Dung Le\*, Khai Nguyen\*, Trang Nguyen\*, Nhat Ho*<br/>

**[O.1]** [Hierarchical Sliced Wasserstein Distance](https://arxiv.org/abs/2209.13570). ICLR, 2023 <br/>
*Khai Nguyen, Tongzheng Ren, __Huy Nguyen__, Litu Rout, Tan Nguyen, Nhat Ho*<br/>

</details>
