---
title: "Automated Chronic Wounds Medical Assessment and Tracking Framework Based on Deep Learning"
authors:
- Brayan Monroy
- Karen Sanchez
- admin
- Juan Estupiñan
- Jorge Bacca
- Claudia V. Correa
- Laura Valencia
- Juan C. Castillo
- Olinto Mieles
- Henry Arguello
- Sergio Castillo
- Fernando Rojas-Morales

author_notes:
reading_time: false
date: "2023-10-01T00:00:00Z"
doi: "10.1016/j.compbiomed.2023.107335"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Elsevier: Computers in Biology and Medicine"
publication_short: ""

abstract: Chronic wounds are a latent health problem worldwide, due to high incidence of diseases such as diabetes and Hansen. Typically, wound evolution is tracked by medical staff through visual inspection, which becomes problematic for patients in rural areas with poor transportation and medical infrastructure. Alternatively, the design of software platforms for medical imaging applications has been increasingly prioritized. This work presents a framework for chronic wound tracking based on deep learning, which works on RGB images captured with smartphones, avoiding bulky and complicated acquisition setups. The framework integrates mainstream algorithms for medical image processing, including wound detection, segmentation, as well as quantitative analysis of area and perimeter. Additionally, a new chronic wounds dataset from leprosy patients is provided to the scientific community. Conducted experiments demonstrate the validity and accuracy of the proposed framework, with up to 84.5% in precision.

# Summary. An optional shortened abstract.
summary: 'Journal on Elsevier: Computers in Biology and Medicine'


featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S0010482523008004'
url_code: 'https://github.com/simatec-uis/CO2Dnet'
url_dataset: 'https://data.mendeley.com/datasets/compare/s2w7rjwz49'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: "center"
  preview_only: true



# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [simatec]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
subsection: "he"
show_breadcrumb: true
---

### Proposed Method 
![screen reader text](/simatec/SIMATEC_arquitactura.png "General scheme of the proposed CO2Dnet deep learning-based framework for automatic segmentation and measurement of chronic wounds in skin ulcers, from RGB images acquired with traditional built-in smartphone cameras.")

### Qualitative results
![screen reader text](/simatec/steps.png "Step-by-step visual results of the proposed framework for six images from the CO2Wounds data set (rows). Each column corresponds to one step of the framework.")
