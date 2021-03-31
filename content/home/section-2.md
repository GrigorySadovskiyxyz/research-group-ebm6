---
# Documentation: https://wowchemy.com/docs/page-builder/
widget: slider
weight: 30

widget: slider
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 500px

item:
  - title: 2000+ выпускников
    content: 'успешно завершили обучение на кафедре с 1995 года. Кого готовим? Где работают? Чем отличаемся?'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#666'  # An HTML color value.
    overlay_img: 001.jpg # Image path relative to your `assets/media/` folder
    image_position: center
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Узнать подробнее
    cta_url: 'https://example.org'
    cta_icon_pack: fas
    cta_icon: graduation-cap
  - title: Left
    content: 'I am left aligned 😄'
    align: center
    overlay_color: '#555'
    overlay_img: '006.jpg'
    overlay_filter: 0.5
  - title: Right
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
---