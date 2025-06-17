---
title: 'Comparing Open-Source UDS Implementations Through Fuzz Testing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Levent Çelik
  - John McShane
  - Christian Scott
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
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *SAE World Congress Experience 2024*
publication_short: In *WCX'24*

abstract: In the ever-evolving landscape of automotive technology, the need for robust security measures and dependable vehicle performance has become paramount with connected vehicles and autonomous driving. The Unified Diagnostic Services (UDS) protocol is the diagnostic communication layer between various vehicle components which serves as a critical interface for vehicle servicing and for software updates. Fuzz testing is a dynamic software testing technique that involves the barrage of unexpected and invalid inputs to uncover vulnerabilities and erratic behavior. This paper presents the implementation of fuzz testing methodologies on the UDS layer, revealing the potential vulnerabilities that could be exploited by malicious entities. By employing both open-source and commercial fuzzing tools and techniques, this paper simulates real-world scenarios to assess the UDS layer’s resilience against anomalous data inputs. Specifically, we deploy several open-source UDS implementations on a Controller Area Network (CAN) testbed and use them as a target for the aforementioned fuzzing tools. The outcomes of the fuzzing campaigns provide both automakers and researchers with insights about the completeness of open-source UDS implementations, as well as existing vulnerabilities. Our recommendations are intended to inform researchers and developers about the current state of these implementations, especially if they consider integrating them into their products. Ultimately, the use of open-source implementations in the automotive domain promises a more secure, easier to maintain, safer, and cheaper development process. This paper underscores the significance of continuous testing and fortification in ensuring the integrity of automotive systems with a particular focus on UDS, offering a valuable contribution to the advancement of secure vehicular technology.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/ccelik-2024-comparing/SAE_UDS_Paper.pdf'
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

