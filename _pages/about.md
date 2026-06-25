---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a Research Scientist at Meta FAIR in Menlo Park. I study how to make **language models reason better while using less compute**. My current work focuses on two questions: how can we teach models to reflect on their own reasoning process using RL, and how can we serve capable models efficiently through quantization, compression, and compact architectures.

These questions are grounded in my PhD work at NYU, where I studied generalization through the lens of information theory and compression. I showed that compression is not just a practical tool for efficiency but can also explain when and how deep learning models generalize, producing the first non-vacuous generalization bounds for billion-parameter LLMs.

My research was recognized with an **ICML 2022 Outstanding Paper Award** for my work on _[Bayesian model selection](https://arxiv.org/abs/2202.11678)_ and a **Best Paper Award** at the ICML 2024 Theoretical Foundations Workshop for my work on _[understanding generalization in LLMs through the lens of compression](https://arxiv.org/abs/2407.18158)_. I was distinguished as a [Rising Star in EECS by MIT](https://risingstars-eecs.mit.edu/participants/sanae-lotfi/ ) and a [Rising Star in Machine Learning](https://www.cs.umd.edu/rising-stars-in-ml-2023 ) by UMD.

I completed my PhD at NYU with [Andrew Gordon Wilson](https://cims.nyu.edu/~andrewgw/ ), supported by the [Microsoft Research PhD Fellowship](https://www.microsoft.com/en-us/research/academic-program/phd-fellowship/ ) and the [Google DeepMind Fellowship](https://www.deepmind.com/scholarships ). Prior to NYU, I worked with [Andrea Lodi](https://tech.cornell.edu/people/andrea-lodi/ ) and [Dominique Orban](https://dpo.github.io/ ) at Polytechnique Montreal on optimization for large-scale machine learning ([Best Master's Thesis Award](https://sanaelotfi.github.io/files/awards/best_thesis_award.pdf )).

**You can contact me at sanaelotfi[at]meta[dot]com**
________

### Recent News 

📢 October 2025: I gave a talk on _Understanding Generalization through the Lens of Compression_ at the [Princeton Alg-ML Seminar](https://princeton-alg-ml.github.io/). 

🥳 September 2025: _[Small Batch Size Training for Language Models](https://arxiv.org/abs/2507.07101)_ got accepted to NeurIPS!

🥳 July 2025: I joined Meta Superintelligence Labs as a Research Scientist, working in the Fundamental AI Research (FAIR) team. 

📑 July 2025: _[Small Batch Size Training for Language Models](https://arxiv.org/abs/2507.07101)_ is now on arxiv!

⭐ May 2025: I gave a **Rising Star** talk at the [International Symposium on Trustworthy Foundation Models](https://istfm.github.io/index.html) @ MBZUAI. 

🥳 May 2025: _[Customizing the Inductive Biases of Softmax Attention using
Structured Matrices](https://openreview.net/pdf?id=Roc5O1ECEt)_ got accepted to ICML!

👩‍🎓 April 2025: I successfully defended my Ph.D. thesis on _Understanding Generalization in Deep Learning Through Occam's Razor_!

📢 December 2024: I'm a **keynote speaker** and **panelist** at the [Machine Learning and Compression Workshop](https://neuralcompression.github.io/workshop24) @ NeurIPS 2024. 

📆 December 2024: I'm organizing the [Scientific Methods for Understanding Neural Networks Workshop](https://scienceofdlworkshop.github.io/) @ NeurIPS 2024. 

🥳 September 2024: Our latest work _[Unlocking Tokens as Data Points for Generalization Bounds on Larger Language Models](https://arxiv.org/abs/2407.18158)_ got accepted to NeurIPS as a **spotlight**! 

⭐ August 2024: I was selected as a **[Rising Star in EECS](https://risingstars-eecs.mit.edu/current-workshop/)** by MIT. 

🏆 July 2024: _[Unlocking Tokens as Data Points for Generalization Bounds on Larger Language Models](https://arxiv.org/abs/2407.18158)_ won the **Best Paper Award** at the ICML Theoretical Foundations Workshop. 

📢 June 2024: I gave a talk on _Non-Vacuous Generalization Bounds for Large Language Models_ at ML Collective. 

👩‍💻 June 2024: I started my summer internship at Microsoft Research NYC, where I will be working on large language model merging for multi-task learning. 

🥳 May 2024: _[Non-Vacuous Generalization Bounds for Large Language Models](https://arxiv.org/abs/2312.17173)_ got accepted to ICML! 

📢 May 2024: I gave a talk on _Non-Vacuous Generalization Bounds for Large Language Models_ at Cohere for AI and UIUC ML Reading group. 

________

### Selected Publications  

**[Small Batch Size Training for Language Models: When Vanilla SGD Works, and Why Gradient Accumulation Is Wasteful](https://arxiv.org/abs/2507.07101)** \
Martin Marek, **Sanae Lotfi**, Aditya Somasundaram, Andrew Gordon Wilson, Micah Goldblum \
_NeurIPS 2025_ \
[[arxiv](https://arxiv.org/abs/2407.18158), [code](https://github.com/martin-marek/batch-size)]

**[Unlocking Tokens as Data Points for Generalization Bounds on Larger Language Models](https://arxiv.org/abs/2407.18158)** \
**Sanae Lotfi<sup>\*</sup>**, Yilun Kuang<sup>\*</sup>, Brandon Amos, Micah Goldblum, Marc Finzi, Andrew Gordon Wilson \
_NeurIPS 2024_ \
🌟 **Spotlight Presentation**  \
_ICML Workshop on Theoretical Foundations of Foundation Models, 2024_ \
🏆 **Best Paper Award** \
[[arxiv](https://arxiv.org/abs/2407.18158), [code](https://github.com/YilunKuang/token-bounds-for-llms)]

**[Non-Vacuous Generalization Bounds for Large Language Models](https://arxiv.org/abs/2312.17173)** \
**Sanae Lotfi<sup>\*</sup>**, Marc Finzi<sup>\*</sup>, Yilun Kuang<sup>\*</sup>, Tim G. J. Rudner, Micah Goldblum, Andrew Gordon Wilson \
_ICML 2024_ \
[[arxiv](https://arxiv.org/abs/2312.17173), [code](https://github.com/Sanaelotfi/sublora-bounds-for-llms)]

**[Bayesian Model Selection, the Marginal Likelihood, and Generalization](https://arxiv.org/abs/2202.11678)** \
**Sanae Lotfi**, Pavel Izmailov, Gregory Benton, Micah Goldblum, Andrew Gordon Wilson \
_ICML 2022, JMLR 2023_ \
🏆 **ICML Outstanding Paper Award, JMLR Best Papers Track** \
[[arxiv](https://arxiv.org/pdf/2202.11678.pdf), [code](https://github.com/Sanaelotfi/Bayesian_model_comparison), <a href="https://sanaelotfi.github.io/files/posters/LML_Poster_ICML_2022.pdf" target="_blank">poster</a>, [talk](https://slideslive.com/38983095/bayesian-model-selection-the-marginal-likelihood-and-generalization), <a href="https://sanaelotfi.github.io/files/slides/conference_presentations/LML_Sanae_Lotfi_ICML_2022.pdf" target="_blank">slides</a>]

**[PAC-Bayes Compression Bounds So Tight That They Can Explain Generalization](https://arxiv.org/abs/2211.13609)** \
**Sanae Lotfi<sup>\*</sup>**, Marc Finzi<sup>\*</sup>, Sanyam Kapoor<sup>\*</sup>, Andres Potapczynski<sup>\*</sup>, Micah Goldblum, Andrew Gordon Wilson \
_NeurIPS 2022_ \
[[arxiv](https://arxiv.org/abs/2211.13609), [code](https://github.com/activatedgeek/tight-pac-bayes)]

**[Dangers of Bayesian Model Averaging under Covariate Shift](https://arxiv.org/abs/2106.11905)** \
Pavel Izmailov, Patrick Nicholson, **Sanae Lotfi**, Andrew Gordon Wilson \
_NeurIPS 2021_ \
[[arxiv](https://arxiv.org/abs/2106.11905), [code](https://github.com/izmailovpavel/bnn_covariate_shift), <a href="https://sanaelotfi.github.io/files/posters/BMA_Dangers_Poster_NeurIPS_2021.pdf" target="_blank">poster</a>]

**[Loss Surface Simplexes for Mode Connecting Volumes and Fast Ensembling](https://arxiv.org/abs/2102.13042)** \
Gregory W. Benton, Wesley J. Maddox, **Sanae Lotfi**, Andrew Gordon Wilson \
_ICML 2021_ \
🌟 **Spotlight Presentation** \
[[arxiv](https://arxiv.org/abs/2102.13042), [code](https://github.com/g-benton/loss-surface-simplexes), <a href="https://sanaelotfi.github.io/files/slides/conference_presentations/Loss_Surface_Simplexes_ICML_2021.pdf" target="_blank">slides</a>]

**[Stochastic First and Second Order Optimization Methods for Machine Learning](https://publications.polymtl.ca/5457/)** \
**Sanae Lotfi** \
_Master's Thesis, Polytechnique Montreal 2020_ \
🏆 **Best Thesis Award** 
  
