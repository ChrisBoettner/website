---
title: An Analytical Model Linking Galaxy and Halo Evolution From z = 10 - 0
summary:
tags:
  - Galaxy Evolution
  - High-z
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: //
---
This is my initial first-year project as a PhD student. The idea is to create a simple analytical model that connects galaxy evolution to the evolution of the dark matter structures by connecting the Halo Mass Function (HMF), i.e. the number density of halos at various halo masses, to the distribution function of some galaxy properties. One would expect the galaxy property connection to be intrinsically connected to the HMF, but modified by intrinsic baryonic processes within the galaxy, so that the distribution function of the galaxy property is given by
\begin{equation}
\Phi_\mathrm{galaxy} (q(m_\mathrm{h})) = \Phi_\mathrm{Halo}(q(m_\mathrm{h})) \cdot \ f(m_\mathrm{h}),
\end{equation}
where we for simplicity assume that the strength of the feedback $f$ soley depends on the halo mass $m_\mathrm{h}$. In this research, we primarely focus on the galaxy stellar mass function (SMF) and galaxy UV luminosity function (UVLF). To our current understanding, these properties are strongly influenced by intrinsic baryonic processes, particularly Stellar and AGN feedback. The goal of the project therefore is to quantify the effects and evolution of these feedback processes in a computationally inexpensive and flexible way.