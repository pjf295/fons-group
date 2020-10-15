---
title: Density-Functional Theory
summary: ab-initio calculations of material properties, structure, and dynamics.
tags:
- DFT
- PCM
date: "2020-10-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Charge density difference plot for a GeTe. Charge pileup indicates a covalent bond.
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

Density-functional theory (DFT) is used to predict a variety of material properties. In addition,
ab-initio molecular dynamics based upon DFT is used to examine structural dynamics and
to generate metastable (amorphous phases) by means of a melt-quench process. The plane-wave codes
VASP (Vienna Ab initio Simulation Package), CASTEP (CAmbridge Serial Total Energy Package),
as well as the FP-(L)APW+lo code Wien2K are used to investigate both structural and electronic
properties of samples under study. In addition the real-space Greens function code Feff9 and 
FMDNES codes are used for the simulation of x-ray absorption data. The figure above shows the charge-density difference (CDD)
for a cross-section of the GeTe lattice which has both short and long bonds. The CDD plot is constructed
by taking the difference between the charge density of the solid and pseudo-atoms. As such the pileup
of charge between two atoms is suggestive of a covalent bond as describe by Pauling.
