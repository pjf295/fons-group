---
title: 機械学習された力場
summary: 材料特性、構造、力学のab-initio計算。
tags:
- DFT
- Machine Learning
date: "2024-05-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: CEGANN機械学習モデルは、3Dネットワーク内のサイトを結晶性か非晶質かを識別する。
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


O密度汎関数理論の注意点の一つは、計算によって大量の出力が得られることである。そのため 
出力の複雑さと量により、生成された出力の解釈に課題が生じることがある。ここでは
この例では、CEGANN: Crystal Edge Graph Attention Neural Network for multiscale classification of materials environment[1]を使用しています、
この例では、注目ベースのアーキテクチャにおいて、原子間の結合と結合角情報を数学的グラフで表現する。
次に、これらのグラフを畳み込みニューラルネットワークの入力層として導入し、三次元構造中の原子に関する局所環境を「学習」する。
を学習する。を使用して生成された非晶質構造および結晶構造で学習することで、分子動力学による
分子動力学法を用いて生成されたアモルファス構造と結晶構造で学習することで、3次元ネットワーク内の部位の性質を、結晶性かアモルファス性かを区別することができる。
アモルファスであることを区別することができる。

ある学生は卒業論文で、CEGANNニューラルネットワークを使って、大規模分子動力学計算における核形成の開始を同定した。
 大規模な分子動力学計算を行った。


[1] S. Banik, D. Dhabal, H. Chan, S. Manna, M. Cherukara, V. Molinero, and S. K. R. S. Sankaranarayanan.
 Cegann: Crystal edge graph attention neural network for multiscale classification of materials environment. NPJ Computational Materials, 9(1):23, 2023.

