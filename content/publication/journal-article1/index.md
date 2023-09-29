---
title: "Reinforcement Learning-Based Cascade Motion Policy Design for Robust 3D Bipedal Locomotion"
authors:
  - Guillermo A. Castillo
  - Bowen Weng
  - Ayonga Hereid
  - Wei Zhang
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: ""
doi: "10.1109/ACCESS.2022.3151771"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*"
publication_short: ""

abstract: This paper presents a novel reinforcement learning (RL) framework to design cascade feedback control policies for 3D bipedal locomotion. Existing RL algorithms are often trained in an end-to-end manner or rely on prior knowledge of some reference joint or task space trajectories. Unlike these studies, we propose a policy structure that decouples the bipedal locomotion problem into two modules that incorporate the physical insights from the nature of the walking dynamics and the well-established Hybrid Zero Dynamics approach for 3D bipedal walking. As a result, the overall RL framework has several key advantages, including lightweight network structure, sample efficiency, and less dependence on prior knowledge. The proposed solution learns stable and robust walking gaits from scratch and allows the controller to realize omnidirectional walking with accurate tracking of the desired velocity and heading angle. The learned policies also perform robustly against various adversarial forces applied to the torso and walking blindly on a series of challenging and unstructured terrains. These results demonstrate that the proposed cascade feedback control policy is suitable for navigation of 3D bipedal robots in indoor and outdoor environments.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/9714352
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://www.youtube.com/watch?v=ocAZtHr07Fw

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
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
slides: ''
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
