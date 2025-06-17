---
title: 'Avoiding the Crash: A Vision-Language Model Evaluation of Critical Traffic
  Scenarios'
authors:
- David Fernandez
- Pedram MohajerAnsari
- Amir Salarpour
- admin
date: '2025-01-01'
publishDate: '2025-06-17T02:03:12.832946Z'
publication_types:
- paper-conference
abstract: Autonomous Vehicles (AVs) have transformed transportation by reducing human error and enhancing traffic efficiency, driven by deep neural network (DNN) models that power image classification and object detection. However, to maintain optimal performance, these models require periodic re-training; failure to do so can result in malfunctions that may lead to accidents. Recently, Vision-Language Models (VLMs), such as LLaVA-7B and MoE-LLaVA, have emerged as powerful alternatives, capable of correlating visual and textual data with a high degree of accuracy. These models’ robustness and ability to generalize across diverse environments make them especially suited to analyzing complex driving scenarios like crashes. To evaluate the decision-making capabilities of these models across common crash scenarios, a set of real-world crash incident videos was collected. By decomposing these videos into frame-by-frame images, we task the VLMs to determine the appropriate driving action at each frame; accelerate, brake, turn left, turn right, or maintain the current course. For each frame, three sets of outputs are analyzed; the actual action executed in the video, the action a human driver would likely take to avoid a crash, and the action the VLM predicts as optimal to avoid a crash. To measure and compare the effectiveness of the VLMs, we introduce a metric called Crash Prevention Efficiency (CPE) which evaluates the model’s performance in detecting crash scenarios and taking appropriate actions to avoid them. CPE assesses how well a VLM can respond to potential crashes by analyzing both the timing of the detection and the proximity to a predefined point in the crash sequence. Our findings reveal that VLMs demonstrate a high level of consistency in decision-making, with LLaVA-7B and MoE-LLaVA models identifying potential crash scenarios 1.13 to 1.33 seconds earlier than humans, respectively. This highlights their potential role in autonomous driving systems (ADS), supporting both real-time decision-making for human drivers and fully autonomous operations.
url_pdf: 'publication/fernandez-2025-avoiding/2025-01-8213.pdf'
---
