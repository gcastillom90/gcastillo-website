---
title: 'Hybrid Zero Dynamics Inspired Feedback Control Policy Design for 3D Bipedal Locomotion using Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Guillermo A. Castillo
  - Bowen Weng
  - Ayonga Hereid
  - Wei Zhang

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
doi: '10.1109/ICRA40945.2020.9197175'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-05-31T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2020 International Conference on Robotics and Automation (ICRA)*
# publication_short: In *ICRA*

abstract: This paper presents a novel model-free reinforcement learning (RL) framework to design feedback control policies for 3D bipedal walking. Existing RL algorithms are often trained in an end-to-end manner or rely on prior knowledge of some reference joint trajectories. Different from these studies, we propose a novel policy structure that appropriately incorporates physical insights gained from the hybrid nature of the walking dynamics and the well-established hybrid zero dynamics approach for 3D bipedal walking. As a result, the overall RL framework has several key advantages, including lightweight network structure, short training time, and less dependence on prior knowledge. We demonstrate the effectiveness of the proposed method on Cassie, a challenging 3D bipedal robot. The proposed solution produces stable limit walking cycles that can track various walking speed in different directions. Surprisingly, without specifically trained with disturbances to achieve robustness, it also performs robustly against various adversarial forces applied to the torso towards both the forward and the backward directions.

# # Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/1910.01748

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=GOT6bnxqwuU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# projects:
#   - example


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
