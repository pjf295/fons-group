---
title: Machine Learned Force Fields
summary: Using machine learned force fields to speed-up molecular dynamics runs
tags:
- DFT
- Machine Learning
date: "2024-05-20T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: メルトクエンチされたセレクタ構造のミッドギャップ状態への寄与を解析した。
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


我々のグループで使用しているVienna ab-initio Simulation Package
(VASP)のようなab-initio平面波コードの計算コストは一般にO(N<sup>3</sup>)
で成長する。このスケーリングは、アモルファス構造を生成するために原子の大きなクラ
スターを異なる速度で溶融と急冷を繰り返す分子動力学シミュレーションでは特に困難と
なります。ab-initio* による小規模なシミュレーションを基に、カーネルベースの機械学習力場をVASP内で学習
させることにより、シミュレーションを2～3桁高速化することができ、ab-initio*
のみを使用した場合よりも、メルト・クエンチ・
ダイナミクスの広範な探索が可能になります。図では、VASPを用いて生成したアモルファ
スクラスターを用いて、Poole-Frenkelのような伝導機構の基礎となるミッドギャップ状態への原子の寄与を行っています。


[1] S. Hatayama, Y. Saito, P. Fons, Y. Shuang, M. Kim, and Y. Sutou. Origins of midgap states in te-based ovonic threshold switch materials. Acta Materialia, 258:119209, 2023.
