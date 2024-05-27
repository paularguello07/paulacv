---
title: 'Video-Tensor Completion using a Deep Learning approach'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - David Morales
  - Yesid Fonseca
  - Henry Arguello

# Author notes (optional)
author_notes:
reading_time: false

date: '2020-08-07T00:00:00Z'
doi: '10.1109/ColCACI50549.2020.9247929'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-07T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*
show_breadcrumb: true
abstract: The tensor completion problem solves the recovery of corrupted data in a multidimensional array named as a tensor. The traditional approaches in tensor completion are based on the transform tensor singular value decomposition(tt-SVD). These approaches minimize the tensor nuclear norm in a domain of an orthogonal transformation to induce low tensorial rank representation. Hence, they require previous knowledge of the data to ensure a low tensor rank representation and, therefore, to ensure a good quality reconstruction. On the other hand, based on the wide progress of deep learning in diverse contexts, this paper presents a 3DU-Net architecture for tensor data recovery in the problem of grayscale videos. The proposed method consists of convolutional layers with 3D filters to take advantage of the information at the spatio-temporal dimensions. The experimental results show that the proposed method has better performance in relative error (RE), peak-to-signal-ratio (PSNR), and less runtime compared with the state-of-the-art solutions. In particular, in the presence of noise, our proposed approach improves the recovery in up to 5.99 dB, and 0.09 in the RE with an 85% of corrupted pixels. In the noiseless case, the proposed architecture improves in 4.39 dB and 0.07 in the RE, when an 85% of the data is lost. Furthermore, the proposed method shows to be faster than the state-of-the-art in the reconstruction time in at least 2.5 times.

# Summary. An optional shortened abstract.
summary: 2020 IEEE Colombian Conference on Applications of Computational Intelligence (IEEE ColCACI 2020)



# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9247929'
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
  placement: 3
  focal_point: 'left'
  preview_only: false



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

