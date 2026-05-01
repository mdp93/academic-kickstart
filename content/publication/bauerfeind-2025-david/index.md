---
title: 'David vs. Goliath: A comparative study of different-sized LLMs for code generation
  in the domain of automotive scenario generation'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Philipp Bauerfeind
- Amir Salarpour
- David Fernandez
- Pedram MohajerAnsari
- Johannes Reschke
- admin

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-05-01T05:00:37.197322Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- preprint

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint arXiv:2510.14115*'
publication_short: ''

doi: ''

abstract: 'Scenario simulation is central to testing autonomous driving systems. Scenic, a domain-specific language (DSL) for CARLA, enables precise and reproducible scenarios, but NL-to-Scenic generation with large language models (LLMs) suffers from scarce data, limited reproducibility, and inconsistent metrics. We introduce NL2Scenic, an open dataset and framework with 146 NL/Scenic pairs, a difficulty-stratified 30-case test split, an Example Retriever, and 14 prompting variants (ZS, FS, CoT, SP, MoT). We evaluate 13 models: four proprietary (GPT-4o, GPT-5, Claude-Sonnet-4, Gemini-2.5-pro) and nine open-source code models (Qwen2.5Coder 0.5B-32B; CodeLlama 7B/13B/34B), using text metrics (BLEU, ChrF, EDIT-SIM, CrystalBLEU) and execution metrics (compilation and generation), and compare them with an expert study (n=11). EDIT-SIM correlates best with human judgments; we also propose EDIT-COMP (F1 of EDIT-SIM and compilation) as a robust dataset-level proxy that improves ranking fidelity. GPT-4o performs best overall, while Qwen2.5Coder-14B reaches about 88 percent of its expert score on local hardware. Retrieval-augmented prompting, Few-Shot with Example Retriever (FSER), consistently boosts smaller models, and scaling shows diminishing returns beyond mid-size, with Qwen2.5Coder outperforming CodeLlama at comparable scales. NL2Scenic and EDIT-COMP offer a standardized, reproducible basis for evaluating Scenic code generation and indicate that mid-size open-source models are practical, cost-effective options for autonomous-driving scenario programming.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://arxiv.org/pdf/2510.14115'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
