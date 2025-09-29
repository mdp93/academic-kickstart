---
title: 'Enhancing Security Through Task Migration in Software-Defined Vehicles'
authors:
- Mohammad Hamad
- Zain AH Hammadeh
- Davide Alessi
- Monowar Hasan
- admin 
- Daniel Lüdtke
- Sebastian Steinhorst
date: '2025-09-18'
publishDate: '2025-09-18T02:03:12.864974Z'
publication_types:
- journal-article
publication: '*IEEE Internet of Things Journal*'
url_pdf: 'publication/hamad-2025-enhancing/shiftguard_final.pdf'
abstract: The growing trend of software-controlled operation, control, and development of modern vehicles has led to the emergence of the software-defined vehicle (SDV) design paradigm. SDVs contain increasing software components and, like other cyber-physical systems, are more susceptible to cyber-attacks. However, patching vulnerabilities in these systems may take time, exposing them to cyber threats. To limit the effect of an attack, one solution is to migrate critical tasks co-located on the same electronic control unit (ECU) with a compromised component to another ECU. However, existing migration solutions, often designed for fault tolerance, introduce overhead and ignore security parameters. This paper introduces ShiftGuard, a security-aware, distributed task migration mechanism for SDVs. We explore various design decisions that may affect the performance of ShiftGuard. We implemented and demonstrated the efficacy of ShiftGuard on an automotive platform running the controller area network (CAN) protocol and found that the end-to-end latency of the task migration decision is less than 17 ms for a system with 15 tasks hosted in 3 ECUs. We also performed extensive design-space exploration using a custom-developed simulator. Our experiments with synthetic workloads show that any task migration request has a 76%-100% success rate. Additionally, we demonstrate ShiftGuard’s scalability for large networks of up to 70 ECUs, making it highly suitable for automotive systems with SDV capabilities.
featured: true
---
