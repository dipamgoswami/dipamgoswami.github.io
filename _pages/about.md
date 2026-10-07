---
layout: about
title: about
permalink: /

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

I am a postdoctoral researcher in the [Learning and Machine Perception (LAMP)](http://lamp.cvc.uab.es/) group at the [Computer Vision Center](https://www.cvc.uab.es/), Barcelona. I work on **Vision-Language Models (VLMs)** and **Multimodal Large Language Models (MLLMs)**, with a broader interest in **understanding and improving the representations** of large foundation models. I also work on **Continual Learning** which studies how deep learning models can keep learning from new data over time without forgetting what they already know, with a particular focus on understanding and controlling how their **embedding spaces** change as they learn.

#### Recent research

My recent works focuses on multimodal and generative models: 

- **Vision-Language Models:** studying cross-modal alignment in contrastive VLMs and exploring training-free approaches.
  - Improving intra-modal alignment in CLIP by decomposing CLIP's projection layers ([IsoCLIP - CVPR 2026](https://arxiv.org/abs/2603.19862)).
  - Improving few-shot image classification using cross-modal prototypes exploiting a task-semantic image subspace ([Project and Mix - Preprint](https://arxiv.org/abs/2603.24528)).
- **Continual Learning with VLMs:** a survey and taxonomy beyond forgetting ([Preprint](https://arxiv.org/pdf/2508.04227?)) and exploiting the semantic knowledge of pre-trained text-encoders ([Preprint](https://arxiv.org/pdf/2408.01076)).
- **Data Attribution with Diffusion Models:** mirrored unlearning approach for training data attribution, i.e. tracing which training data influences a generated output ([MUCS - NeurIPS 2026](https://arxiv.org/pdf/2605.17938)).

#### PhD research

My PhD focused on how models learn when data is not available all at once: arriving over time or spread across clients. I developed efficient methods that work **without storing old data, without re-training, or with minimal communication**, by studying how embedding spaces change during learning:

- **Continual Learning:** exemplar-free class-incremental learning ([FeCAM - NeurIPS 2023](https://arxiv.org/pdf/2309.14062)), few-shot class-incremental learning ([CVPRW 2024](https://arxiv.org/pdf/2404.06622?)) and compensating for feature drift ([ADC - CVPR 2024](https://arxiv.org/pdf/2405.19074), [LDC - ECCV 2024](https://arxiv.org/pdf/2407.08536)).
- **Federated Learning:** training-free, communication-efficient methods built on pre-trained models ([FedCOF - NeurIPS 2025](https://arxiv.org/pdf/2412.14326)).
- **Information Retrieval:** continual learning of dense retrieval embedding models that stay compatible with existing embedding indexes ([QDC - CoLLAs 2025](https://arxiv.org/pdf/2506.00037)).

Before starting my PhD, I worked on continual learning for object detection ([ICCV 2023](https://arxiv.org/pdf/2307.12427)) and semantic segmentation ([WACV 2023](https://arxiv.org/pdf/2210.07207)), defect detection in SEM images ([SPIE Advanced Lithography 2022](https://arxiv.org/pdf/2206.13505)), cell detection from urine microscopic images ([ISBI 2023](https://arxiv.org/pdf/2211.06104), [UMID dataset](https://arxiv.org/pdf/2111.10374)) and graph-based approaches for generation of dimensioned floorplans ([AI EDAM 2021](https://www.cambridge.org/core/journals/ai-edam/article/abs/graphbased-approach-for-enumerating-floorplans-based-on-users-specifications/C1632000D36BD0D0C1FA9E44584F1F00), [SCCE 2024](https://www.jsoftcivil.com/article_196433.html)).

#### Background

I completed my [PhD](https://www.tdx.cat/handle/10803/697395) in April 2026 at the [Computer Vision Center](https://www.cvc.uab.es/), Universitat Autònoma de Barcelona, supervised by [Joost van de Weijer](https://scholar.google.com/citations?user=Gsw2iUEAAAAJ&hl=en) and [Bartłomiej Twardowski](https://scholar.google.com/citations?user=8yywECgAAAAJ&hl=en), with the thesis *Understanding the Embedding Space in Continual and Federated Learning*. Before that, I received a B.E. in Computer Science and an M.Sc. in Mathematics from [BITS Pilani](https://www.bits-pilani.ac.in/pilani/), India in 2022.


#### Research visits and industry experience

- **[Sony AI](https://ai.sony/)** Barcelona (2025): research internship on training data attribution for Diffusion Models with [Joan Serrà](https://scholar.google.com/citations?user=sZLj96sAAAAJ&hl=en&oi=ao).
- **[KU Leuven, PSI group](https://www.esat.kuleuven.be/psi)** Belgium (2025): research stay on Vision-Language Models with [Tinne Tuytelaars](https://scholar.google.com/citations?user=EuFF9kUAAAAJ&hl=en&oi=ao) and [Gido van de Ven](https://scholar.google.com/citations?user=3k0l15MAAAAJ&hl=en&oi=ao).
- **[IDEAS NCBR](https://ideas-ncbr.pl/en/)** Warsaw (2024): research stay on continual learning of dense retrieval embedding models with [Bartłomiej Twardowski](https://scholar.google.com/citations?user=8yywECgAAAAJ&hl=en).
- **[DFKI](https://www.dfki.de/web)** Kaiserslautern, Germany (2022): research assistant in the [Augmented Vision Group](https://www.dfki.de/web/forschung/forschungsbereiche/erweiterte-realitaet) under [Didier Stricker](https://scholar.google.com/citations?user=ImhXfxgAAAAJ&hl=en) where I worked on continual learning for semantic segmentation.

#### Recognition and talks

- Invited talk on **Understanding the Embedding Space in Continual, Federated and Multimodal Learning** at the [MICC](https://www.micc.unifi.it) seminar, University of Florence (2026).
- Gave talks on **Exemplar‑Free Continual Learning** at the [GMUM](https://gmum.net) seminar, Jagiellonian University, Kraków (2024); at the [Data Science Summit](https://ml.dssconf.pl/), Warsaw (2024), at the CVML reading sessions at the University of Barcelona (2024) and at the [Deep Learning Barcelona Symposium](https://sites.google.com/view/dlbcn2023/) (2023).
- Top reviewer at NeurIPS 2024 and outstanding reviewer at BMVC 2024.
- Innovation award (team "Continual Learners") at the Continual Test-time Adaptation challenge, [Visual Continual Learning Workshop](https://wvcl.vis.xyz/), ICCV 2023, where I also gave an oral presentation.

#### Community service

- I served as a reviewer for ICML, ICLR, NeurIPS, AISTATS, CoLLAs, CVPR, ICCV, ECCV, WACV and BMVC, and for journals including IEEE TPAMI, IJCV, TMLR, IEEE TNNLS and IEEE TIP.
- I co-organize the [CoLLAs Seminars](https://lifelong-ml.cc/seminar), a monthly online seminar series on lifelong learning launched in May 2026.


**I am open to postdoctoral and research scientist positions starting in January 2027. Feel free to [reach out](mailto:dgoswami@cvc.uab.es).**

