---
title: 'HW/SW Co-Design of an Automotive Embedded Firewall'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Karsten Schmidt
  - Udo Dannebaum

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2017-04-01T00:00:00Z'
#doi: '10.1145/3319535.3363190'

# Schedule page publish date (NOT publication's date).
#publishDate: '2021-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *SAE World Congress Experience 2017*
publication_short: In *WCX'17*

abstract: The automotive industry experiences a major change as vehicles are gradually becoming a part of the Internet. Security concepts based on the closed-world assumption cannot be deployed anymore due to a constantly changing adversary model. Automotive Ethernet as future in-vehicle network and a new E/E Architecture have different security requirements than Ethernet known from traditional IT and legacy systems. In order to achieve a high level of security, a new multi-layer approach in the vehicle which responds to special automotive requirements has to be introduced. One essential layer of this holistic security concept is to restrict non-authorized access by the deployment of embedded firewalls. This paper addresses the introduction of automotive firewalls into the next-generation domain architecture with a focus on partitioning of its features in hardware and software. Based on the deployment of the firewall in the in-vehicle network, the corresponding adversary model and automotive requirements such as latency, jitter, CPU load and memory consumption are going to be discussed. Drivers behind these metrics are primarily safety concerns and cost and thus are relevant for both OEMs and hardware manufacturers. As a result, a reasonable implementation of an automotive firewall system has to be a trade-off between hardware and software in order to meet the above-named automotive requirements. We implemented the firewall on an Infineon AURIX TriCore and Altera Cyclone V FPGA to analyze these metrics. The paper shows the options and decision points to find an optimal partitioning between hardware and software for an automotive embedded firewall system.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/firewall/SAE_Firewall_Paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'publication/firewall/SAE_Firewall_Presentation.pdf'
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

