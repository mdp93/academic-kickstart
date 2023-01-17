---
title: 'Security Analysis of Android Automotive'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Kang G. Shin
  - Josiah Bruner
  - Amy Chu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-03-01T00:00:00Z'
#doi: '10.1145/3485832.3485883'

# Schedule page publish date (NOT publication's date).
#publishDate: '2021-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *SAE International Journal of Advances and Current Practices in Mobility, 2/2020*
publication_short: In *SAEJ'20*

abstract: In-vehicle infotainment (IVI) platforms are getting increasingly connected. Besides OEM apps and services, the next generation of IVI platforms are expected to offer integration of third-party apps. Under this anticipated business model, vehicular sensor and event data can be collected and shared with selected third-party apps. To accommodate this trend, Google has been pushing towards standardization among proprietary IVI operating systems with their Android Automotive platform which runs natively on the vehicle’s IVI platform. Unlike Android Auto’s limited functionality of display-projecting certain smartphone apps to the IVI screen, Android Automotive will have access to the in-vehicle network (IVN), and will be able to read and share various vehicular sensor data with third-party apps. This increased connectivity opens new business opportunities for both the car manufacturer as well as third-party businesses, but also introduces a new attack surface on the vehicle. Therefore, Android Automotive must have a secure system architecture to prevent any potential attacks that might compromise the security and privacy of the vehicle and the driver. In particular, malicious third-party entities could remotely compromise a vehicle's functionalities and impact the vehicle safety, causing financial and operational damage to the vehicle, as well as compromise the driver’s privacy and safety. This paper presents an Android Automotive system architecture and provides guidelines for conducting a high-level security analysis. It also describes what countermeasures have already been taken by Google to prevent potential attacks, and discusses what still needs to be done in order to offer a secure and privacy-preserving Android experience for next-generation IVI platforms.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/aaos_security/SAE_Android_Automotive_Paper.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'publication/aaos_security/SAE_Android_Automotive_Presentation.pdf'
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

