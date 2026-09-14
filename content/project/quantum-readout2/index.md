---
title: Quantum read-out
summary: How to characterize and certify quantum systems through measurements with limited resources?

# Short title used in page links (if not set, defaults to title)
title_short: 

authors:
- gaerttner
- euler
- dachille
- jung
- goerguen
- braeu
- naumann
- menhofer

# Determines ordering of projects
weight: 7

# Optional external URL for project (replaces project detail page).
external_link: ""

tags:
#- topics
#- ultracold atoms
#- quantum mechanics

image:
  caption: ""
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

math: true
---

The efficient characterization of quantum states and processes through measurements is central to quantum technologies; be it to certify relevant resources like entanglement, or to extract relevant observables in quantum simulation experiments. A challenge arises due to the fundamental difference of quantum measurements and measurements on classical objects. Fully characterizing a quantum system requires preparing multiple copies of the same state and measuring these with different measurement settings. When applied to composite quantum systems this procedure becomes infeasible beyond a handful of particles due to the large number of required experimental runs.

We develop strategies to overcome this obstacle, for example, by exploiting prior knowledge about the quantum system at hand. Among all possible quantum states, most are very unlikely to occur in a given experimental situation. We seek to exploit this by building models that parameterize only the set of relevant states, so that the parameters of these models can then be inferred efficiently from measurements. For this, we often build on machine-learning techniques which are suitable to recognize and exploit the relevant physical structures.


