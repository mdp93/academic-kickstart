---
title: 'S2-CAN: Sufficiently Secure Controller Area Network'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jay W. Schauer
  - Junhui Li
  - Kang G. Shin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-12-01T00:00:00Z'
#doi: '10.1145/3485832.3485883'

# Schedule page publish date (NOT publication's date).
#publishDate: '2021-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Annual Computer Security Applications Conference 2021*
publication_short: In *ACSAC'21*

abstract: As automotive security concerns are rising, the Controller Area Network (CAN) — the de facto standard of in-vehicle communication protocol — has come under scrutiny due to its lack of encryption and authentication. Several vulnerabilities, such as eavesdropping, spoofing, and replay attacks, have shown that the current implementation needs to be extended. Both academic and commercial solutions for a Secure CAN (S-CAN) have been proposed, but OEMs have not yet integrated them into their products. The main reasons for this lack of adoption are their heavy use of limited computational resources in the vehicle, increased latency that can lead to missed deadlines for safety-critical messages, as well as insufficient space available in a CAN frame to include a Message Authentication Code (MAC). By making a trade-off between security and performance, we develop S2-CAN, which overcomes the aforementioned problems of S-CAN. We leverage protocol-specific properties of CAN instead of using cryptographic primitives and design a “sufficiently secure” alternative CAN with minimal overhead on resources and latency. We evaluate the security of S2-CAN in four real-world vehicles by an automated vehicular attack tool.We finally show that CAN security can be guaranteed by the correct choice of a design parameter while achieving acceptable performance.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/pese-2021-s-2/ACSAC_S2-CAN_Paper.pdf'
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

