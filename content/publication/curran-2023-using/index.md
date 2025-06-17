---
title: 'Using Phone Sensors to Augment Vehicle Reliability'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Noah T. Curran
  - Arun Ganesan
  - admin
  - Kang G. Shin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-10-01T00:00:00Z'
#doi: '10.1145/3319535.3363190'

# Schedule page publish date (NOT publication's date).
#publishDate: '2021-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE Conference on Communications and Network Security (CNS)*
publication_short: In *CNS'23*

abstract: The increasing connectivity of vehicles has led to wide exploitation of their vulnerability/unreliability surface. As a result, the security and reliability of vehicle sensor information has become a pressing concern because of the importance of sensor information to vehicular functions. To address this concern, state-of-the-art anomaly detectors validate vehicle sensors via the information internal to a vehicle. However, they are still prone to data unreliability as vehicles are built with little to no sensor redundancy. To further enhance the reliability of vehicle sensors, we present CaRe 1 which uses the driver’s smartphone as an external source of sensor redundancy for detecting vehicle sensor anomalies. CaRe uses sensing capabilities available in smartphones to estimate vehicle sensor values and ensures smartphone sensing to be resilient to common phone usage to improve the accuracy of estimations. It logs anomalies and informs the driver of detected anomalies to limp home and/or to inspect later. Using injections on vehicle sensor traces, CaRe is empirically shown to detect anomalies from 5 safety-critical vehicle sensors with high true positive rates (for sudden injections, range from 97.33% for speed to 90.08% for gear) while keeping the false positive rates very low (almost always less than 1%). CaRe can estimate vehicle sensors and detect anomalies with low computational overhead (≈ 8% CPU usage) and low time latency (bottlenecked by the sensor refresh rate). 1 Pronounced like “care,” CaRe stands for “Car Reliability.”

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/curran-2023-using/CNS_CaRe_Paper.pdf'
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

