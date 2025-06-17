---
title: LLM-Powered Fuzz Testing of Automotive Diagnostic Protocols
authors:
- John McShane
- Levent Celik
- Iwinosa Aideyan
- Richard Brooks
- admin
date: '2025-01-01'
publishDate: '2025-06-17T02:03:12.839701Z'
publication_types:
- paper-conference
abstract: Modern vehicles contain tens of different Electronic Control Units (ECUs) from several vendors. These small computers are connected through several networking busses and protocols, potentially through gateways and converters. In addition, vehicle-to-vehicle and internet connectivity are now considered requirements, adding additional complexity to an already complex electronic system. Due to this complexity and the safety-critical nature of vehicles, automotive cyber-security is a difficult undertaking. One critical aspect of cyber-security is the robust software testing for potential bugs and vulnerabilities. Fuzz testing is an automated software testing method injecting large input sets into a system. It is an invaluable technique across many industries and has become increasingly popular since its conception. Its success relies highly on the “quality” of inputs injected. One shortcoming associated with fuzz testing is the expertise required in developing “smart” fuzz testing tools (fuzzers). Developing a fuzzer requires expertise on various topics, from input types and underlying networks to potential system configurations. Moreover, fuzzers are generally not transferable between different systems, limiting their reuse. This study investigates whether Generative AI technologies can meaningfully assist in their development by comparing an AI-generated fuzzer against a commercial one. An automotive fuzzer focusing on Unified Diagnostic Services (UDS) was developed by exclusively querying an AI model. First, the pre-trained AI is taught the underlying structure and constraints of UDS and is then used to generate semantically valid test cases. The effectiveness of test cases for vulnerability and fault detection is evaluated. The impact of specific queries and the underlying protocol network configurations on the generated test cases is then investigated through comparison with a commercial fuzzer.
url_pdf: 'publication/mcshane-2025-llm/2025-01-8091.pdf'
---
