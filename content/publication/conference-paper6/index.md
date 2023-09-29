---
title: 'On Safety Testing, Validation, and Characterization with Scenario-Sampling: A Case Study of Legged Robots'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bowen Weng
  - Guillermo A. Castillo
  - Wei Zhang
  - Ayonga Hereid
  

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
doi: '10.1109/IROS47612.2022.9981359'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2022 International Conference on Intelligent Robots and Systems (IROS)*
# publication_short: In *ICRA*

abstract: The dynamic response of the legged robot locomotion is non-Lipschitz and can be stochastic due to environmental uncertainties. To test, validate, and characterize the safety performance of legged robots, existing solutions on observed and inferred risk can be incomplete and sampling inefficient. Some formal verification methods suffer from the model precision and other surrogate assumptions. In this paper, we propose a scenario sampling based testing framework that characterizes the overall safety performance of a legged robot by specifying (i) where (in terms of a set of states) the robot is potentially safe, and (ii) how safe the robot is within the specified set. The framework can also help certify the commercial deployment of the legged robot in real-world environment along with human and compare safety performance among legged robots with different mechanical structures and dynamic properties. The proposed framework is further deployed to evaluate a group of state-of-the-art legged robot locomotion controllers from various model-based, deep neural network involved, and reinforcement learning based methods in the literature. Among a series of intended work domains of the studied legged robots (e.g. tracking speed on sloped surface, with abrupt changes on demanded velocity, and against adversarial push-over disturbances), we show that the method can adequately capture the overall safety characterization and the subtle performance insights. Many of the observed safety outcomes, to the best of our knowledge, have never been reported by the existing work in the legged robot literature.

# # Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: https://arxiv.org/abs/2103.15309

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=j8KbW-a9dbw'

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
# projects:
#   - example
projects: []

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
