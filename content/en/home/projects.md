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
There are several ongoing themes present in the Fons research group some of which are listed
below. The basic theme is to understand 
atomic level structure and use the resulting understanding to optimize functionality. This includes the use
of synchrotron radiation to investigate the physical and electronic structure of solids using tools
such as x-ray absorption spectroscopy (XAFS) or high-energy photoemission spectroscopy. 
XAFS is a technique particular useful for understanding the structure of amorphous solids.
Ultrafast dynamics has also been a topic of interest with collaborative efforts including 
using the free-electron laser SACLA at SPring-8, coherent phonon dynamics, or
ab-initio molecular dynamics calculations. In addition to the use of *ab-initio* based computational
techniques in recent years, the Fons group has used machine learning techniques both to predict 
good candidate materials for experiments such as selector materials as well as for the analysis
of large datasets of molecular dynamic data. The use of machine learning techniques allows
not only large improvements in the speed of analyzing large *ab-initio* computational datasets, but
also large increases in the speed and size of molecular dynamics calculations by means of
the use of machine-learned force fields based upon *ab-initio* calculations.

