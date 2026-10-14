---
title: Numerical simulation methods
summary: How to efficiently simulate quantum many-body physics on classical computers?

# Short title used in page links (if not set, defaults to title)
title_short: 

authors:
- gaerttner
- euler
- jung
- erpelding
- goerguen

# Determines ordering of projects
weight: 3

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

Quantum many-body problems are generically hard for classical computers as the Hilbert space grows exponentially with system size, making brute-force simulation quickly intractable. Yet, clever approximate methods can be surprisingly powerful. For weakly interacting systems, mean-field and perturbative approaches capture the essential physics; more broadly, methods with controlled errors are also invaluable for benchmarking quantum simulators.

Our focus is on variational simulation methods, built on a simple but powerful observation: Physically relevant quantum states occupy only a tiny corner of the full Hilbert space. So, rather than navigating the whole space, we represent the quantum state within a much lower-dimensional subspace, as illustrated in the figure. The central challenge is designing ansatzes that encode the right physical prior knowledge about the relevant class of states. We use neural networks for this purpose: their expressiveness makes them natural candidates for capturing complex quantum correlations, and we apply them to find ground states and simulate the dynamics of open quantum systems.


