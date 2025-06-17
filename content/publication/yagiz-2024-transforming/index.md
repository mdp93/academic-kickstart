---
title: 'Transforming In-Vehicle Network Intrusion Detection: VAE-based Knowledge Distillation
  Meets Explainable AI'
authors:
- Muhammet Anil Yagiz
- Pedram MohajerAnsari
- admin
- Polat Goktas
date: '2024-01-01'
publishDate: '2025-06-17T02:03:12.815161Z'
publication_types:
- paper-conference
publication: '*Proceedings of the Sixth Workshop on CPS&IoT Security and Privacy*'
abstract: In the evolving landscape of autonomous vehicles, ensuring robust in-vehicle network (IVN) security is paramount. This paper introduces an advanced intrusion detection system (IDS) called KD-XVAE that uses a Variational Autoencoder (VAE)-based knowledge distillation approach to enhance both performance and efficiency. Our model significantly reduces complexity, operating with just 1669 parameters and achieving an inference time of 0.3 ms per batch, making it highly suitable for resource-constrained automotive environments. Evaluations in the HCRL Car-Hacking dataset demonstrate exceptional capabilities, attaining perfect scores (Recall, Precision, F1 Score of 100%, and FNR of 0%) under multiple attack types, including DoS, Fuzzing, Gear Spoofing, and RPM Spoofing. Comparative analysis on the CICIoV2024 dataset further underscores its superiority over traditional machine learning models, achieving perfect detection metrics. We furthermore integrate Explainable AI (XAI) techniques to ensure transparency in the model's decisions. The VAE compresses the original feature space into a latent space, on which the distilled model is trained. SHAP (SHapley Additive exPlanations) values provide insights into the importance of each latent dimension, mapped back to original features for intuitive understanding. Our paper advances the field by integrating state-of-the-art techniques, addressing critical challenges in the deployment of efficient, trustworthy, and reliable IDSes for autonomous vehicles, ensuring enhanced protection against emerging cyber threats.
url_pdf: 'publication/yagiz-2024-transforming/Yagiz_XAI.pdf'
---
