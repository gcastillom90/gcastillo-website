---
title: 'MELP: Model Embedded Linear Policies for Robust Bipedal Hopping'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Raghav Soni  
  - Guillermo A. Castillo
  - Lokesh Krishna
  - Ayonga Hereid
  - Shishir Kolathaya
# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 International Conference on Intelligent Robots and Systems (IROS)*
# publication_short: In *ICRA*

abstract: Linear policies are the simplest class of policies that can achieve stable bipedal walking behaviors in both simulation and hardware. However, a significant challenge in deploying them widely is the difficulty in extending them to more dynamic behaviors like hopping and running. Therefore, in this work, we propose a new class of linear policies in which template models can be embedded. In particular, we show how to embed Spring Loaded Inverted Pendulum (SLIP) model in the policy class and realize perpetual hopping in arbitrary directions. The spring constant of the template model is learned in addition to the remaining parameters of the policy. Given this spring constant, the goal is to realize hopping trajectories using the SLIP model, which are then tracked by the bipedal robot using the linear policy. Continuous hopping with adjustable heading direction was achieved across different terrains in simulation with heading and lateral velocities of up to 0.5m/sec and 0.05m/sec, respectively. The policy was then transferred to the hardware, and preliminary results (> 10 steps) of hopping were achieved.

# # Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
# - name: arXiv
#   url: 'https://arxiv.org/abs/2309.15740'

url_pdf: ''
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
