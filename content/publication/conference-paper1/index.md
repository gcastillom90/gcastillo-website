---
title: 'Reinforcement Learning Meets Hybrid Zero Dynamics: A Case Study for RABBIT'

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
doi: '10.1109/ICRA.2019.8793627'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-05-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2019 International Conference on Robotics and Automation (ICRA)*
# publication_short: In *ICRA*

abstract: The design of feedback controllers for bipedal robots is challenging due to the hybrid nature of its dynamics and the complexity imposed by high-dimensional bipedal models. In this paper, we present a novel approach for the design of feedback controllers using Reinforcement Learning (RL) and Hybrid Zero Dynamics (HZD). Existing RL approaches for bipedal walking are inefficient as they do not consider the underlying physics, often requires substantial training, and the resulting controller may not be applicable to real robots. HZD is a powerful tool for bipedal control with local stability guarantees of the walking limit cycles. In this paper, we propose a non traditional RL structure that embeds the HZD framework into the policy learning. More specifically, we propose to use RL to find a control policy that maps from the robot’s reduced order states to a set of parameters that define the desired trajectories for the robot’s joints through the virtual constraints. Then, these trajectories are tracked using an adaptive PD controller. The method results in a stable and robust control policy that is able to track variable speed within a continuous interval. Robustness of the policy is evaluated by applying external forces to the torso of the robot. The proposed RL framework is implemented and demonstrated in OpenAI Gym with the MuJoCo physics engine based on the well-known RABBIT robot model.

# # Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/1810.01977

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=dhHMfnl7YlU'

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
projects:
  - example

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
