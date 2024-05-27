+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Projects"
subtitle = "Current Research Themes"

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
    [[content.filter_button]]
    name = "All"
    tag = "*"
  
    [[content.filter_button]]
      name = "TDMC"
      tag = "TDMC"
  
   [[content.filter_button]]
     name = "Phase-Change"
     tag = "PCM"
  
   [[content.filter_button]]
     name = "Amorphous Materials"
     tag = "Amorphous"
     
   [[content.filter_button]]
     name = "Ultrafast"
     tag = "ultrafast"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
フォンス研究グループには、現在進行中のテーマがいくつかある。
その一部を以下に紹介する。基本テーマは 
原子レベルの構造を理解し、その結果得られた理解を使って機能を最適化することである。これには
放射光を用いたX線吸収分光法のようなツールを用いて、固体の物理的・電子的構造を調べることである。
X線吸収分光法（XAFS）や高エネルギー光電子分光法などがある。
XAFSは特にアモルファス固体の構造を理解するのに有効な手法である。
超高速ダイナミクスもまた、以下のような共同研究によって注目されている。
SPring-8の自由電子レーザーSACLA、コヒーレントフォノンダイナミクス、ab-initio分子動力学計算を含む共同研究が行われている。
ab-initio分子動力学計算などである。ab-initio*ベースの計算手法の使用に加えて、近年では
近年、フォンス・グループは、ab-initio*に基づく計算手法の使用に加え、機械学習技術を使用して、以下のような実験に適した候補物質を予測している。
を予測したり、分子動力学データの大規模なデータセットを解析したりするために、機械学習技術を使用してきた。
分子動力学データの大規模なデータセットの解析にも使用している。機械学習技術の使用により
大規模な*ab-initio*計算データセットの解析速度の大幅な向上だけでなく
分子動力学計算のスピードとサイズを大幅に向上させることができる。
ab-initio*計算に基づく機械学習された力場の使用により、分子動力学計算のスピードとサイズを大幅に向上させることができる。


