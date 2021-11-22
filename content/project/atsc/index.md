---
title: Large-scale Traffic Signal Control Using Multi-Agent Reinforcement Learning
summary: Multi-Agent Reinforcement Learning for Adaptive Traffic Signal Control
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Adaptive Traffic Signal Control
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://twitter.com/georgecushen
- icon: ""
  icon_pack: ""
  name: Report
  url: https://twitter.com/georgecushen
- icon: ""
  icon_pack: ""
  name: Presentation
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This the scalability issues centralized RL systems face when applied to large-scale automatic traffic signal control due to the extremely high dimension of the joint action space. The project applied Multi-agent RL to overcome the scalability issues by distributing the global control to each local RL agent. Local agents consisted of Deep-Q Learning agents. The solution was compared against existing methods via simulation of a large synthetic grid of the KNUST campus. The proposed solution showed comparable performance to the state-of-the-art and better performance than existing traffic signal control methods when taking into account average intersection delay and average queue length.
