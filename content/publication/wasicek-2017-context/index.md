---
title: 'Context-aware Intrusion Detection in Automotive Control Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Armin Wasicek
  - admin
  - Andre Weimerskirch
  - Yelizaveta Burakova
  - Karan Singh

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2017-06-01T00:00:00Z'
#doi: '10.1145/3319535.3363190'

# Schedule page publish date (NOT publication's date).
#publishDate: '2021-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *5th escar USA 2017*
publication_short: In *escar'17*

abstract: This paper describes a method and framework to detect manipulations in automotive control systems. As the automotive industry is shifting towards employing software-based solutions, the incentives for attackers to manipulate automotive systems. The boundary where the cyber and physical world interface is particularly sensitive for security and safety. Manipulations in the computer system might have an uncontrollable impact in the physical environment and could lead to potentially dangerous situations. This paper presents a context-aware intrusion detection system (CAID) framework capable to recognize manipulations of the physical system using cyber means. CAID uses sensor information to establish reference models of the physical system and then checks correctness of current sensor data against the reference models. Thereby, it establishes the notion of plausibility of a controller’s operation. CAID augments today’s cyber physical intrusion detection systems (IDS) by adding a physical model to the detection engine. The CAID framework has been evaluated in a vehicular setup using test vehicle. Telemetry data has been collected from a test vehicle that has then been chip-tuned with a commercially available chip-tuning tool to obtain manipulated data. CAID was able to recognize the chip tuning with a very high probability using an unsupervised Artificial Neural Network (ANN). This proof-of-concept could be the starting point to enhance current automotive IDS using the CAID framework in order to detect future automotive attacks to safety-critical systems.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/wasicek-2017-context/Escar17_CAID_Paper.pdf'
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

