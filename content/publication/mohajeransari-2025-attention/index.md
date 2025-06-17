---
title: Attention-Aware Temporal Adversarial Shadows on Traffic Sign Sequences
authors:
- Pedram MohajerAnsari
- Amir Salarpour
- David Fernandez
- Cigdem Kokenoz
- Bing Li
- admin
date: '2025-01-01'
publishDate: '2025-06-17T02:03:12.852238Z'
publication_types:
- paper-conference
publication: '*The 5th Workshop of Adversarial Machine Learning on Computer Vision:
  Foundation Models + X*'
url_pdf: 'https://openaccess.thecvf.com/content/CVPR2025W/AdvML/papers/MohajerAnsari_Attention-Aware_Temporal_Adversarial_Shadows_on_Traffic_Sign_Sequences_CVPRW_2025_paper.pdf'
abstract: We present a framework for black-box adversarial attacks on traffic signs using dynamic, temporally coherent shadows. Unlike prior work that focuses on single-image attacks or relies on conspicuous physical artifacts, our method operates over entire image sequences, mimicking realistic scenarios where a traffic sign is observed from varying distances. We design a non-differentiable shadow generator that casts a single fixed-shape, fixed-opacity shadow whose spatial scale evolves over time to simulate natural environmental shading. A genetic algorithm is used to optimize shadow geometry and opacity, guided by a dual loss that jointly maximizes classification error and visual attention disruption. Attention perturbation is measured using DINO ViT attention maps between clean and shadowed frames. Evaluated on the GTSRB dataset, our method achieves a sequence-level attack success rate (SL-ASR) — defined as the percentage of sequences where at least τ out of T frames are misclassified — ranging from 52.3% to 87.5%, depending on the threshold and shadow type. Furthermore, incorporating attention supervision yields consistent SL-ASR gains of 11–18% over purely classification-based attacks
---
