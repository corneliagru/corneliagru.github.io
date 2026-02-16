---
title: "Revisiting Active Learning under (Human) Label Variation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Helen Alber
  - Bernd Bischl
  - Göran Kauermann
  - Barbara Plank
  - Matthias Aßenmacher

date: '2025-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Gruber, C., Alber, H., Bischl, B., Kauermann, G., Plank, B. & Aßenmacher, M. Revisiting Active Learning under (Human) Label Variation. In Proceedings of the The 4th Workshop on Perspectivist Approaches to NLP 75–86 (Association for Computational Linguistics, Suzhou, China, 2025)
publication_short: In Proceedings of the The 4th Workshop on Perspectivist Approaches to NLP 75–86 (Association for Computational Linguistics, Suzhou, China, 2025)

abstract: Access to high-quality labeled data remains a limiting factor in applied supervised learning. Active learning (AL), a popular approach to optimizing the use of limited annotation budgets in training ML models, often relies on at least one of several simplifying assumptions, which rarely hold in practice when acknowledging human label variation (HLV). Label variation (LV), i.e., differing labels for the same instance, is common, especially in natural language processing. Yet annotation frameworks often still rest on the assumption of a single ground truth, overlooking HLV, i.e., the occurrence of plausible differences in annotations, as an informative signal. In this paper, we examine foundational assumptions about truth and label nature, highlighting the need to decompose observed LV into signal (e.g., HLV) and noise (e.g., annotation error). We survey how the AL and (H)LV communities have addressed---or neglected---these distinctions and propose a conceptual framework for incorporating HLV throughout the AL loop, including instance selection, annotator choice, and label representation. We further discuss the integration of large language models (LLM) as annotators. Our work aims to lay a conceptual foundation for (H)LV-aware active learning, better reflecting the complexities of real-world annotation.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Natural Language Processing
  - Active Learning
  - Label Variation
  - Uncertainty

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2025.nlperspectives-1.7.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
