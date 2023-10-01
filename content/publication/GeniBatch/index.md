---
title: "Accelerating Privacy-Preserving Machine Learning with GeniBatch"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Minel Huang

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *EuroSys*
publication_short: In *EuroSys*

abstract: Cross-silo privacy-preserving machine learning (PPML) adopts Partial Homomorphic Encryption (PHE) for secure data combination and high-quality model training across multiple organizations (e.g., medical and financial). However, PHE introduces significant computation and communication overheads due to the data inflation problem. Batch optimization is an encouraging direction to mitigate the problem by compressing multiple data into a single ciphertext. While promising, it is impractical for a large number of cross-silo PPML applications due to the limited vector operations support and severe data corruption. In this paper, we present GeniBatch, a batch compiler that translates a PPML program with PHE into an efficient program with batch optimization. GeniBatch adopts a set of conversion rules to allow PHE programs involving all vector operations required in cross-silo PPML and ensures end-to-end result consistency before/after compiling. By proposing bit-reserving algorithms, GeniBatch avoids bit-overflow for the correctness of compiled programs and maximizes the compression ratio. We have fully integrated GeniBatch into FATE, an industrial cross-silo PPML framework, and provided SIMD APIs to harness hardware acceleration. Experimental results of six popular applications show that GeniBatch achieves up to 22.6x speedup and reduce network traffic by 5.4x-23.8x for general cross-silo PPML applications.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
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
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
