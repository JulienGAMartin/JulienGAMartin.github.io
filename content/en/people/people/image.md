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
  columns: "3"
#   background:
#     image: 
#     image_darken: 0
#     image_parallax: false
#     image_position: center
#     image_size: contain
#     text_color_light: true
#   spacing:
#     padding: ["20px", "0", "20px", "0"]
# advanced:
#   css_class: fullscreen

gallery_item:
- album: lab_pics
  image: 500-21_1_sqebc.jpg
  caption: SQEBC 2021, Sherbrooke
- album: lab_pics
  image: 499-22_1_thib_pt.jpg
  caption: Potluck fall 2022, Gatineau 
- album: lab_pics
  image: 498-22_2_sqebc.jpg
  caption: SQEBC 2022, Ottawa
- album: lab_pics
  image: 497-22_3_sqebc.jpg
  caption: SQEBC 2022, Gatineau
---


<center>{{< gallery album = "lab_pics" >}}</center>

