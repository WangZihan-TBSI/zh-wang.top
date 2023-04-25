---
title: Multiscale-VR: Multiscale Gigapixel 3D Panoramic Videography for Virtual Reality
authors: 
- Jianing Zhang
- Tianyi Zhu
- Anke Zhang
- Xiaoyun Yuan
- admin
- Sebastian Beetschen
- Lan Xu
- Xing Lin
- Qionghai Dai
- Lu Fang
author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2020-04-24T00:00:00Z'
doi: 'http://10.1109/ICCP48838.2020.9105244'
# Schedule page publish date (NOT publication's date).
publishDate: '2019-06-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: IEEE

abstract: Creating virtual reality (VR) content with effective imaging systems has attracted significant attention worldwide following the broad applications of VR in various fields, including entertainment, surveillance, sports, etc. However, due to the inherent trade-off between field-of-view and resolution of the imaging system as well as the prohibitive computational cost, live capturing and generating multiscale 360◦ 3D video content at an eye-limited resolution to provide immersive VR experiences confront significant challenges. In this work, we propose Multiscale-VR, a multiscale unstructured camera array computational imaging system for high-quality gigapixel 3D panoramic videography that creates the six-degree-of-freedom multiscale interactive VR content. The Multiscale-VR imaging system comprises scalable cylindrical-distributed global and local cameras, where global stereo cameras are stitched to cover 360◦ field-of-view, and unstructured local monocular cameras are adapted to the global camera for flexible high-resolution video streaming arrangement. We demonstrate that a high-quality gigapixel depth video can be faithfully reconstructed by our deep neural network-based algorithm pipeline where the global depth via stereo matching and the local depth via high-resolution RGB-guided refinement are associated. To generate the immersive 3D VR content, we present a three-layer rendering framework that includes an original layer for scene rendering, a diffusion layer for handling occlusion regions, and a dynamic layer for efficient dynamic foreground rendering. Our multiscale reconstruction architecture enables the proposed prototype system for rendering highly effective 3D, 360◦ gigapixel live VR video at 30 fps from the captured high-throughput multiscale video sequences. The proposed multiscale interactive VR content generation approach by using a heterogeneous camera system design, in contrast to the existing single-scale VR imaging systems with structured homogeneous cameras, will open up new avenues of research in VR and provide an unprecedented immersive experience benefiting various novel applications.

# Summary. An optional shortened abstract.
summary: 

tags:
 - Virtual Reality
 - Deep Learning

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'papers/ICCP.pdf'
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
  caption: ''
  focal_point: ''
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
