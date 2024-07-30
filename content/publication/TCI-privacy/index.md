---
title: 'Learning to Describe Scenes via Privacy-aware Designed Optical Lens'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jhon Lopez
  - Karen Sanchez
  - Carlos Hinojosa
  - Fernando Rojas-Morales
  - Henry Arguello


reading_time: false
date: '2024-07-29T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Computational Imaging
publication_short: IEEE TCI

abstract: Scene captioning consists of accurately describing the visual information using text, leveraging the capabilities of computer vision and natural language processing. However, current image captioning methods are trained on high-resolution images that may contain private information about individuals within the scene, such as facial attributes or sensitive data. This raises concerns about whether machines require high-resolution images and how we can protect the private information of the users. In this work, we aim to protect privacy in the scene captioning task by addressing the issue directly from the optics before image acquisition. Specifically, motivated by the emerging trend of integrating optics design with algorithms, we introduce a learned refractive lens into the camera to ensure privacy. Our optimized lens obscures sensitive visual attributes, such as faces, ethnicity, gender, and more, in the acquired image while extracting relevant features, enabling descriptions even from highly distorted images. By optimizing the refractive lens and a deep network architecture for image captioning end-to-end, we achieve description generation directly from our distorted images. We validate our approach with extensive simulations and hardware experiments. Our results show that we achieve a better trade-off between privacy and utility when compared to conventional non-privacy-preserving methods on the COCO dataset. For instance, our approach successfully conceals private information within the scene while achieving a BLEU-4 score of 27.0 on the COCO test set.

# Summary. An optional shortened abstract.
summary: Journal on IEEE Transactions on Computational Imaging



# Display this page in the Featured widget?
featured: True

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'final_document.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'privacy'
url_slides: ''
url_source: 'supplementary_document.pdf'
url_video: ''
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: 'right'
  preview_only: true


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
![screen reader text](/tci-privacy/method.png "Proposed end-to-end model (2PSC). The optical encoder incorporates a camera with a refractive lens, which is parametrized by a linear combination of Zernike Polynomials. The decoder is formed of convolutional feature extraction and a Long Short Term Memory Network with attention, which produces a caption from the private image.")

![screen reader text](/tci-privacy/lab.jpg "(Top) Experimental hardware setup for our proposed privacy-preserving image captioning approach. (Bottom) PSFs and qualitative results on an image example acquired with a conventional camera (left), our proof-of-concept camera (middle), and simulated camera (right).")