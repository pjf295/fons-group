---
title: Machine Learning-based Analysis of ab-initio MD
summary: Using machine learning to analyze crystallization dynamics
tags:
- DFT
- Machine Learning
date: "2024-05-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: A CEGANN machine learning model identifying sites in a 3D network as being crystalline or amorphous.
  focal_point: Smart

l#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---


One of the caveats of density-functional theory is that calculations can produce copious amounts of output. Due to the 
complexity and volume of the output, this can lead to challenges in interpreting the generated output. Here well
use CEGANN: Crystal Edge Graph Attention Neural Network for multiscale classification of materials environment[1] In this example,
we represent bonds between atoms as well as bond angle information in a mathematical graph in an attention based architecture.
These graphs are then introduced as an input layer to a convolutional neural network to "learn" the local environment
about atoms in the three-dimensional structure. By training on amorphous and crystalline structures generated using *ab-initio**
molecular dynamics, the nature of a site in a three-dimensional network can be distinguished as being crystalline or 
amorphous in nature.

In a thesis, a student used a CEGANN neural network to identify the onset of nucleation in
 a large scale molecular dynamics run.


[1] S. Banik, D. Dhabal, H. Chan, S. Manna, M. Cherukara, V. Molinero, and S. K. R. S. Sankaranarayanan.
 Cegann: Crystal edge graph attention neural network for multiscale classification of materials environment. NPJ Computational Materials, 9(1):23, 2023.

