---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

title: Lab gallery
subtitle:

design:
  columns: "1"
  background:
    image: 
    image_darken: 0
    image_parallax: false
    image_position: center
    image_size: contain
    text_color_light: true
  spacing:
    padding: ["20px", "0", "20px", "0"]
advanced:
  css_class: fullscreen
gallery_item:
- album: lab_pics
  image: lab_sqebc_21.jpg
  caption: On the way back from SQEBC 2021
- album: lab_pics
  image: sqebc_22_1.jpg
  caption: SQEBC 2022, Ottawa
- album: lab_pics
  image: sqebc_22_2.jpg
  caption: SQEBC 2022, Gatineau
- album: lab_pics
  image: thib_pt_22.jpg
  caption: Pot luck and mug drawing fun
---
{{< gallery album = "lab_pics" >}}
