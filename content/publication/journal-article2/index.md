---
title: "AdaMap: High-Scalable Real-Time Cooperative Perception at the Edge"
authors:
- Qiang Liu
- admin

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09--01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM SEC "
publication_short: ""

abstract: Cooperative perception is the key approach to augment the perception of connected and automated vehicles (CAVs) toward safe autonomous driving. However, it is challenging to achieve real-time perception sharing for hundreds of CAVs in large-scale deployment scenarios. In this paper, we propose AdaMap, a new high-scalable real-time cooperative perception system, which achieves assured percentile end-to-end latency under time-varying network dynamics. To achieve AdaMap, we design a tightly coupled data plane and control plane. In the data plane, we design a new hybrid localization module to dynamically switch between object detection and tracking, and a novel point cloud representation module to adaptively compress and reconstruct the point cloud of detected objects. In the control plane, we design a new graph-based object selection method to un-select excessive multi-viewed point clouds of objects, and a novel approximated gradient descent algorithm to optimize the representation of point clouds. We implement AdaMap on an emulation platform, including realistic vehicle and server computation and a simulated 5G network, under a 150-CAV trace collected from the CARLA simulator. The evaluation results show that, AdaMap reduces up to 49x average transmission data size at the cost of 0.37 reconstruction loss, as compared to state-of-the-art solutions, which verifies its high scalability, adaptability, and computation efficiency.
# Summary. An optional shortened abstract.
summary: Cooperative perception is the key approach to augment the perception of connected and automated vehicles (CAVs) toward safe autonomous driving. However, it is challenging to achieve real-time perception sharing for hundreds of CAVs in large-scale deployment scenarios. In this paper, we propose AdaMap, a new high-scalable real-time cooperative perception system, which achieves assured percentile end-to-end latency under time-varying network dynamics. To achieve AdaMap, we design a tightly coupled data plane and control plane. In the data plane, we design a new hybrid localization module to dynamically switch between object detection and tracking, and a novel point cloud representation module to adaptively compress and reconstruct the point cloud of detected objects. In the control plane, we design a new graph-based object selection method to un-select excessive multi-viewed point clouds of objects, and a novel approximated gradient descent algorithm to optimize the representation of point clouds. We implement AdaMap on an emulation platform, including realistic vehicle and server computation and a simulated 5G network, under a 150-CAV trace collected from the CARLA simulator. The evaluation results show that, AdaMap reduces up to 49x average transmission data size at the cost of 0.37 reconstruction loss, as compared to state-of-the-art solutions, which verifies its high scalability, adaptability, and computation efficiency.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2309.13526.pdf
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}} -->
<!-- Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software. -->
<!-- {{% /callout %}} -->

<!-- {{% callout note %}} -->
<!-- Create your slides in Markdown - click the *Slides* button to check out the example. -->
<!-- {{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
