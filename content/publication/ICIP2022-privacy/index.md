---
title: 'Optics lens design for privacy-preserving scene captioning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jhon Lopez
  - Carlos Hinojosa
  - Henry Arguello

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
reading_time: false
date: '2022-10-16T00:00:00Z'
doi: '10.1109/ICIP46576.2022.9897555'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2022 IEEE International Conference on Image Processing (ICIP)
publication_short: In ICIP 2022

abstract: Image captioning is a challenging task that connects two major artificial intelligence fields, computer vision and natural language processing. Image captioning models use traditional images to generate a natural language description of the scene. However, the scene could contain private information that we want to hide but still generate the captions. Inspired by the trend of jointly designing optics and algorithms, this paper addresses the problem of privacy-preserving scene captioning. Our approach promotes privacy preservation, by hiding the faces in the images, during the acquisition process with a designed refractive camera lens while extracting useful features to perform image captioning. The refractive lens and an image captioning deep network architecture are optimized end-to-end to generate descriptions directly from the blurred images. Simulations show that our privacy-preserving approach degrades private visual attributes (e.g., face detection fails with our distorted images) while achieving comparable captioning performance with traditional non-private methods on the COCO dataset.

# Summary. An optional shortened abstract.
summary: 2022 IEEE International Conference on Image Processing (ICIP)



# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9897555'
url_code: ''
url_dataset: ''
url_poster: 'poster_icip.pdf'
url_project: ''
url_slides: 'slides_icip-pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [privacy]
show_breadcrumb: true

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

### Best Paper Award ICIP 2022
![screen reader text](/icip2022/image.png )

### Proposed Method 
![screen reader text](/icip2022/model-1.png "Proposed end-to-end (2PSC) model. The optical encoder consists of a camera with a refractive lens. The decoder consists of convolutional feature extraction and an LSTM with attention, which generates a description from the privacy image")

### Qualitative results
![screen reader text](/icip2022/Captions-1.png "Qualitative results on the COCO dataset test set. Under each privacy image, we show the caption obtained by each model, and under the original image, we show the ground truth caption. We compute the PSNR between the original and distorted images for each approach")

### Video
{{< youtube Ls3U-v9Md2U >}}
