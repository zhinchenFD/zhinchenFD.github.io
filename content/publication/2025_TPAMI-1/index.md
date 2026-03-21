---
title: "[TPAMI'25]Context perception parallel decoder for scene text recognition"

# Authors

# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here

# and it will be replaced with their full name and linked to their profile.

authors:
- Yongkun Du
- Zhineng Chen
- Caiyan Jia
- Xiaoting Yin
- Chenxia Li
- Yuning Du
- Yu-Gang Jiang


# Author notes (optional)

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Corresponding author'

date: '2026-3-16T00:00:00Z'
# Schedule page publish date (NOT publication's date).
# publishDate: '2024-03-24T00:00:00Z'
# publishDate: 

# Publication type.

# Accepts a single type but formatted as a YAML list (for Hugo requirements).

# Enter a publication type from the CSL standard.

publication_types: ['paper-Journal']

# Publication name and optional abbreviated publication name.

publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence*
publication_short: In *IEEE TPAMI*

abstract: 

# Summary. An optional shortened abstract.

summary: 

tags: []

# Display this page in the Featured widget?

featured: true

# Custom links (uncomment lines below)

# links:

# - name: Custom Link

# url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10902187/'
url_code: 'https://github.com/Topdu/OpenOCR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image

# To use, add an image named `featured.jpg/png` to your page's folder.

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).

# Associate this publication with one or more of your projects.

# Simply enter your project's folder or file name without extension.

# E.g. `internal-project` references `content/project/internal-project/index.md`.

# Otherwise, set `projects: []`.

# projects:

# - example

# Slides (optional).

# Associate this publication with Markdown slides.

# Simply enter your slide deck's filename without extension.

# E.g. `slides: "example"` references `content/slides/example/index.md`.

# Otherwise, set `slides: ""`.

# slides: example
---
Scene text recognition (STR) methods have struggled to attain high accuracy and fast inference speed. Auto-Regressive (AR)-based models implement the recognition in a character-by-character manner, showing superiority in accuracy but with slow inference speed. Alternatively, Parallel Decoding (PD)-based models infer all characters in a single decoding pass, offering faster inference speed but generally worse accuracy. To realize the dual goals of “AR-level accuracy and PD-level speed”, we propose a Context Perception Parallel Decoder (CPPD) to perceive the related context and predict the character sequence in a PD pass. CPPD devises a character counting module to infer the occurrence count of each character, and a character ordering module to deduce the content-free reading order and positions. Meanwhile, the character prediction task associates the positions with characters. They together build a comprehensive recognition context, which benefits the decoder to focus accurately on characters with the attention mechanism, thereby improving the recognition accuracy. We construct a series of CPPD models and also plug the proposed modules into existing STR decoders. Experiments on both English and Chinese benchmarks demonstrate that the CPPD models achieve highly competitive accuracy while running much faster than existing leading models. Moreover, the plugged models achieve significant accuracy improvements.
