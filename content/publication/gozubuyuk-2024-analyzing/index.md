---
title: Analyzing Privacy Implications of Data Collection in Android Automotive OS
authors:
- Bulut Gözübüyük
- Brian Tang
- Kang G Shin
- admin
date: '2024-01-01'
publishDate: '2025-06-17T02:03:12.789346Z'
publication_types:
- article
publication: '*arXiv preprint arXiv:2409.15561*'
url_pdf: 'https://arxiv.org/pdf/2409.15561'
abstract: Modern vehicles have become sophisticated computation and sensor systems, as evidenced by advanced driver assistance systems, in-car infotainment, and autonomous driving capabilities. They collect and process vast amounts of data through various embedded subsystems. One significant player in this landscape is Android Automotive OS (AAOS), which has been integrated into over 100M vehicles and has become a dominant force in the in-vehicle infotainment market. With this extensive data collection, privacy has become increasingly crucial. The volume of data gathered by these systems raises questions about how this information is stored, used, and protected, making privacy a critical issue for manufacturers and consumers. However, very little has been done on vehicle data privacy. This paper focuses on the privacy implications of AAOS, examining the exact nature and scope of data collection and the corresponding privacy policies from the original equipment manufacturers (OEMs). We develop a novel automotive privacy analysis tool called PriDrive which employs three methodological approaches; network traffic inspection, and both static and dynamic analyses of Android images using rooted emulators from various OEMs. These methodologies are followed by an assessment of whether the collected data types were properly disclosed in OEMs and 3rd party apps' privacy policies (to identify any discrepancies or violations). Our evaluation on three different OEM platforms reveals that vehicle speed is collected at a sampling rate of roughly 25 Hz. Other properties such as model info, climate & AC, and seat data are collected in a batch 30 seconds into vehicle startup. In addition, several vehicle property types were collected without disclosure in their respective privacy policies. For example, OEM A's policies only covers 110 vehicle properties or 13.02% of the properties found in our static analysis.
---
