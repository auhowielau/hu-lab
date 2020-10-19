+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.
location = "left"

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "450px"
bottom_opacity = true

# Choose how many columns the section has. Valid values: 1 or 2.
hugo_logo = "hugo_logo_en.jpg"  # Image path relative to your `static/media/` folder.
hugo_logo2 = "hugo_logo2.png"  # Image path relative to your `static/media/` folder.
hugo_logo3 = "hugo_logo3.png"  # Image path relative to your `static/media/` folder.
logo_title = "视频内容安全研究组"
logo_content = "Vision & Security Laboratory"

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["0", "20px", "0", "20px"]

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Welcome to **VSLab**"
  content = "VSLab has carried out much high-quality research of fundamental theories and innovative methods around 'AI + Security' &nbsp;[**learn more**](/en/projects/)"
  align = "left"  # Choose `center`, `left`, or `right`.
  opacity = 0.8

  # overlay_color = "#333"  # An HTML color value.
  overlay_img = "vs_en.png"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.

[[item]]
  title = "Welcome to **VSLab**"
  content = "Fast Online Object Tracking and Segmentation: A Unifying Approach &nbsp;[**learn more**](http://www.robots.ox.ac.uk/~qwang/SiamMask/)"
  align = "left"  # Choose `center`, `left`, or `right`.
  opacity = 0.8 # 透明度取值0-1

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#666"  # An HTML color value.
  overlay_img = "siammask.gif"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Get Academic"
  # cta_url = "https://sourcethemes.com/academic/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
  title = "Welcome to **VSLab**"
  content = "VOT2018 realtime track winner &nbsp;[**learn more**](/en/project/visualperception)"
  align = "left"  # Choose `center`, `left`, or `right`.
  opacity = 0.8

  # overlay_color = "#333"  # An HTML color value.
  overlay_img = "vot_.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.

[[item]]
  title = "Welcome to **VSLab**"
  content = "VATEX Captioning Challenge 2019 Chinese and English tracks winner &nbsp;[**learn more**](/en/subpage/videocaption)"
  align = "left"  # Choose `center`, `left`, or `right`.
  opacity = 0.8

  # overlay_color = "#333"  # An HTML color value.
  overlay_img = "vatex_.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0  # Darken the image. Value in range 0-1.
+++
