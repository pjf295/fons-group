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
Fons研究グループにはいくつかの進行中のテーマがあり、そのうちのいくつかを以下に示します。基本的なテー
マは、原子レベルの構造を理解し、その結果得られた理解を使用して機能を最適化することです。これには、X
線吸収分光法（XAFS）や高エネルギー光電子分光法などのツールを使用して固体の物理的および電子的構造を調
査するためのシンクロトロン放射の使用が含まれます。
XAFSは、アモルファス固体の構造を理解するのに特に役立つ手法です。超高速ダイナミクスは、SPring-
8での自由電子レーザーSACLAの使用、コヒーレントフォノンダイナミクス、または非経験的分子動力学計算など
の共同作業でも関心のあるトピックです。
