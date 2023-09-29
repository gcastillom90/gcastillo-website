---
title: Reinforcement Learning-Based Policy Design for Robust 3D Bipedal Locomotion

event: Invited Talk at the Laboratory for Intelligent Decision and Autonomous Robots, Georgia Tech
# event_url: https://example.org

location: Laboratory for Intelligent Decision and Autonomous Robots, Georgia Tech
address:
  # street: Online
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States
  postcode: Online

summary: A reinforcement learning (RL) framework to design cascade feedback control policies for 3D robust bipedal locomotion.
abstract: 'In the field of bipedal locomotion, the robustness of the control policy remains one of the biggest challenges when designing locomotion controllers. In general, a robust bipedal locomotion policy can be obtained through model-based approaches, learning-based approaches, or a combination of both. While recent learning-based solutions have shown promising results in achieving dynamic locomotion for bipedal robots, they still suffer from poor sampling efficiency. Most of these approaches rely on end-to-end learning and require previous knowledge of reference trajectories, and only some of them have been successfully deployed in hardware. In this talk, I will present a reinforcement learning (RL) framework to design cascade feedback control policies for 3D bipedal locomotion. By decoupling the problem of bipedal locomotion as a two-phase process: trajectory planning and feedback regulation, we propose a modular solution that incorporates the physical insights of dynamic locomotion and its hybrid nature into the learning process of the policy. We leverage the exploration potential of RL algorithms to find reference trajectories for dynamic locomotion using a reduced state of the robot. Then, we improve these reference trajectories using feedback regulation to obtain stable and robust walking gaits. This decoupled structure significantly simplifies the neural network’s complexity, enhancing sampling efficiency and robustness of the learned policy. The proposed framework learns stable and robust walking gaits from scratch and allows the controller to realize omnidirectional walking with accurate tracking of the desired velocity and heading angle. The learned policies also perform robustly against various adversarial forces applied to the torso and walking blindly on a series of challenging and unstructured terrains.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-04-21T13:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
projects: []
---

