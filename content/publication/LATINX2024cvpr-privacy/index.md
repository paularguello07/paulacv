---
title: 'Learning to Describe Scenes via Privacy-aware Optical Lens'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jhon Lopez
  - Karen Sanchez
  - Carlos Hinojosa
  - Hoover Rueda-Chacón 
  - Henry Arguello


reading_time: false
date: '2024-05-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['extended-abstract']

# Publication name and optional abbreviated publication name.
publication: LatinX in CV (LXCV) Research at CVPR 2024
publication_short: LatinX CVPR 2024

abstract: Image caption generation textually summarizes the visual content of an image. This task has gained popularity at the turning point of computer vision (CV) and natural language processing (NLP). Images used to train image captioning models may contain sensitive data that should be confidential, such as faces, personal characteristics, documents, children, etc. This work focuses on protecting privacy in the image captioning task, directly from the image acquisition stage. For this, a refractive lens was designed to ensure privacy using an end-to-end deep learning-based optimization approach. The designed lens blurs sensitive visual attributes in the acquired image while extracting essential features to generate captions even from highly distorted images. The image caption network implements two long short-term memory networks (LSTMs) with an attention module in between to ensure high-quality captions. This method was tested and validated through simulations in the COCO dataset. The results showed a better balance between privacy and usability compared to traditional methods that do not consider privacy.

# Summary. An optional shortened abstract.
summary: LatinX in CV (LXCV) Research at CVPR 2024



# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'Extended_Abstract_CVPR_LatinX_2024_Privacy_Preserving.pdf'
url_code: ''
url_dataset: ''
url_poster: 'CVPR2024_poster_template (1).pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  placement: 1
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [privacyic]
show_breadcrumb: true

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
