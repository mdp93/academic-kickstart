---
title: 'Bringing Practical Security to Vehicles'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-08-01T00:00:00Z'
#doi: '10.1145/3319535.3363190'

# Schedule page publish date (NOT publication's date).
#publishDate: '2021-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['7']

# Publication name and optional abbreviated publication name.
publication: In *University of Michigan*
#publication_short: In *WCX'19*

abstract: PModern vehicles are getting increasingly connected. Together with more automotive electronics and wireless interfaces, the number of possible attack surfaces increases, raising security concerns. Attacks on cars can have multiple implications, ranging from financial incentives or damage to the compromise of human safety. Although attacks vary, all of them have one component in common, namely CAN bus injection. The CAN bus is the de-facto technology used inside the in-vehicle network to interconnect automotive controllers. An attacker who compromises the CAN bus can inject arbitrary CAN messages to it, making the vehicle misbehave. As a result, countermeasures against the CAN bus attacks need to be implemented by carmakers. Unfortunately, the carmakers have been reluctant to adopt any approach proposed thus far to secure CAN. The main reasons for this reluctance are that (i) CAN injection requires the knowledge of semantics which differs from vehicle to vehicle and is proprietary to the car-makers, as well as (ii) industry-specific functional and cost constraints which have not been reflected in the existing solutions. Any solution that accounts for these constraints has to incur minimal overhead on computational resources and message latency. I address these two points by first showing that proprietary semantics can be automatically reverse-engineered, effectively removing the barrier for CAN injection attacks. I demonstrated this by developing LibreCAN which can quickly and accurately reverse engineer both automotive powertrain- and body-related information in an automated fashion. Adversaries can significantly accelerate their preparation time for a CAN injection attack by obtaining the semantics which car-makers were trying to keep secret by not disclosing it publicly. Second, to meet the industry-specific constraints, I propose S2-CAN and MichiCAN. The former adds confidentiality, authenticity and integrity to the CAN bus without the overhead of cryptography, but by leveraging protocol-specific properties. The latter protects the CAN bus against attacks on its availability, e.g., Denial of Service, by leveraging novel hardware features of automotive controllers. Its main difference from existing work is practicality. Instead of adapting well-known cryptographic techniques from the realm of computer networks which do not satisfy the aforementioned cost and functional constraints, I propose out-of-the-box solutions that leverage protocol- and hardware-based features of automotive networks and controllers. Furthermore, both S2-CAN and MichiCAN are fully backward-compatible with existing hardware and specifications, as well as incur minimal computation and network overheads. CAN injection attacks can also be conducted remotely by accepting malicious data from other cars in vehicle-to-vehicle (V2V) communication scenarios. I propose textbf{CARdea}, a two-phase anomaly detection system that sanitizes incoming data from surrounding vehicles. Compared to computationally-intensive prior work, CARdea combines an in-vehicle light-weight anomaly detection phase with a more resource-heavy machine-learning phase that can be executed on the vehicle, edge or cloud based on available computational resources and manufacturer constraints. Overall, this dissertation demonstrates the omnipresence of CAN injection attacks and develops novel, practical security solutions for CAN and V2X by analyzing the inherent trade-off between security and performance. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/thesis/mpese_thesis.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

