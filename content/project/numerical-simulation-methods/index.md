---
title: Numerical simulation methods
summary: How to efficiently simulate quantum many-body physics on classical computers?

# Short title used in page links (if not set, defaults to title)
title_short: 

authors:
- gaerttner
- jung
- euler
- gorgun
- erpelding

# Determines ordering of projects
weight: 6

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

While solving quantum many-body problems is generally hard for classical computers, one can still get quite far by using suitable approximate simulation methods. For example, for weakly interacting systems, mean-field or perturbative methods can work decently, taking into account interactions only in an approximate manner. Numerical methods for quantum many-body systems which work well in certain regimes and have controlled errors are also important to certify the correct functioning of quantum simulators.

Our goal is to advance such methods with a focus on semiclassical and variational simulation methods. Semiclassical methods exploit that quantum fluctuations can be treated in a perturbative fashion in certain cases. While quantum particles come with an intrinsic uncertainty about their position, the most likely trajectory they will take is still the one predicted by classical physics. In the semi-classical regime, quantum fluctuations around it become small. We exploit this to efficiently simulate spin systems using the so-called discrete truncated Wigner approximation. Variational approaches build on the insight that the physical time evolution of a quantum systems stays confined to a relatively small part of the entire state space. We seek to find parameterizations of the relevant set of states using neural networks to find ground states or to simulate the dynamics of open quantum systems.


