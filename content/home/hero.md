+++
# Hero widget.
widget = "hero"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "**Cross-Modality Domain Adaptation for Medical Image Segmentation**"

# Hero image (optional). Enter filename of an image in the `static/media/` folder.
#hero_media = "pituitaryusschematic.svg"
hero_media = "banner_website.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # King's dark blue text "rgb(10, 45, 80)"
  color = "rgb(0, 0, 0)"
  
  # Background gradient.
  # gradient_start = "#4bb4e3"
  # gradient_end = "#2b94c3"
  
  # Background image.
  #image = "todo.jpeg"  # Name of image in `static/media/`.
  #image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  #image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  #image_position = "center"  # Options include `left`, `center` (default), or `right`.
  #image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "https://www.synapse.org/#!Synapse:syn51236108/wiki/"
  label = "👋 Join crossMoDA 2023!"

[cta_alt]
  url = "https://doi.org/10.1016/j.media.2022.102628"
  label = "The crossMoDA 2021 paper accepted in Medical Image Analysis!"
  icon_pack = "ai"
  icon = "arxiv"

# Note. An optional note to show underneath the links.
# [cta_note]
#  label="👋 [Training Data](https://wowchemy.com/docs/update/)"
+++

Unsupervised 3D Semantic Segmentation Domain Adaptation
