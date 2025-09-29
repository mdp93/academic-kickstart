---
title: 'FedVLM: Scalable Personalized Vision-Language Models through Federated Learning'
authors:
- Arkajyoti Mitra
- Afia Anjum
- Paul Agbaje
- admin
- Habeeb Olufowobi
date: '2025-01-01'
publishDate: '2025-06-17T02:03:12.877516Z'
publication_types:
- paper-conference
publication: "*The European Conference on Artificial Intelligence (ECAI'25)*"
abstract: Vision-language models (VLMs) demonstrate impressive zero-shot and few-shot learning capabilities, making them essential for several downstream tasks. However, fine-tuning these models at scale remains challenging, particularly in federated environments where data is decentralized and non-iid across clients. Existing parameter-efficient tuning methods like LoRA (Low-Rank Adaptation) reduce computational overhead but struggle with heterogeneous client data, leading to suboptimal generalization. To address these challenges, we propose FedVLM, a federated LoRA fine-tuning framework that enables decentralized adaptation of VLMs while preserving model privacy and reducing reliance on centralized training. To further tackle data heterogeneity, we introduce personalized LoRA (pLoRA), which dynamically adapts LoRA parameters to each client's unique data distribution, significantly improving local adaptation while maintaining global model aggregation. Experiments on the RLAIF-V dataset show that pLoRA improves client-specific performance by 24.5% over standard LoRA, demonstrating superior adaptation in non-iid settings. FedVLM provides a scalable and efficient solution for fine-tuning VLMs in federated settings, advancing personalized adaptation in distributed learning scenarios.
url_pdf: 'publication/mitra-2025-fedvlm/FedVLM_ECAI.pdf'
---
