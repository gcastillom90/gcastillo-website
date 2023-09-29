---
title: 'Safe Bipedal Path Planning via Control Barrier Functions for Polynomial Shape Obstacles Estimated Using Logistic Regression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chengyang Peng
  - Octavian Donca
  - Guillermo A. Castillo
  - Ayonga Hereid

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
doi: '10.1109/ICRA48891.2023.10160671'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-29T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 International Conference on Robotics and Automation (ICRA)*
# publication_short: In *ICRA*

abstract: Safe path planning is critical for bipedal robots to operate in safety-critical environments. Common path planning algorithms, such as RRT or RRT*, typically use geometric or kinematic collision check algorithms to ensure collision-free paths toward the target position. However, such approaches may generate non-smooth paths that do not comply with the dynamics constraints of walking robots. It has been shown that the control barrier function (CBF) can be integrated with RRT/RRT*to synthesize dynamically feasible collision-free paths. Yet, existing work has been limited to simple circular or elliptical shape obstacles due to the challenging nature of constructing appropriate barrier functions to represent irregularly shaped obstacles. In this paper, we present a CBF-based RRT* algorithm for bipedal robots to generate a collision-free path through space with multiple polynomial-shaped obstacles. In particular, we used logistic regression to construct polynomial barrier functions from a grid map of the environment to represent irregularly shaped obstacles. Moreover, we developed a multi-step CBF steering controller to ensure the efficiency of free space exploration. The proposed approach was first validated in simulation for a differential drive model, and then experimentally evaluated with a 3D humanoid robot, Digit, in a lab setting with randomly placed obstacles.

# # Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2210.03704

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=r_hkuK5cMw4&feature=youtu.be'

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
