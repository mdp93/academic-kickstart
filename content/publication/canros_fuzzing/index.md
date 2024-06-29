---
title: 'Fuzzing CAN vs. ROS: An Analysis of Single-Component vs. Dual-Component Fuzzing of Automotive Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Iwinosa Aideyan
  - Richard Brooks
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-04-01T00:00:00Z'
#doi: '10.1145/3485832.3485883'

# Schedule page publish date (NOT publication's date).
#publishDate: '2021-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *SAE World Congress Experience 2024*
publication_short: In *WCX'24*

abstract: Robust communications are crucial for autonomous military fleets. Ground vehicles function as mobile local area networks utilizing Controller Area Network (CAN) backbones. Fleet coordination between autonomous platforms relies on the Robot Operating System (ROS) publish/subscribe robotic middleware for effective operation. To bridge communications between the CAN and ROS network segments, the CAN2ROS bridge software supports bidirectional data flow with message mapping and node translation. 

  Fuzzing, a software testing technique, involves injecting randomized data inputs into the target system. This method plays a pivotal role in identifying vulnerabilities. It has proven effective in discovering vulnerabilities in online systems, such as the integrated CAN/ROS system. In our study, we consider ROS implementing zero-trust access control policies, running on a Gazebo test-bed connected to a CAN bus. Our objective is to evaluate system security using fuzzers in three scenarios; (i) fuzzing the CAN bus alone, (ii) fuzzing the CAN bus with a ROS Fuzzer, and (iii) fuzzing both systems simultaneously using the CAN2ROS bridge.

  This paper poses the question; is fuzzing the unified system more effective than fuzzing individual components. By analyzing interactions between the bridge and the military fleets’ CAN systems, we identify and address flaws potentially introduced in the software, or data leakage between communication segments. Our analysis employs experimental design and statistical analysis to shed light on the bridge’s security robustness and its potential implications for the overall system’s integrity.

  This research holds significant implications for both industry and academia. Stakeholders involved in the development of autonomous military and civilian fleets can leverage our findings to enhance system security and reliability. Ultimately, the identification and mitigation of vulnerabilities contribute to safer and more resilient military operations.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/canros_fuzzing/SAE_CANROS_Paper.pdf'
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

