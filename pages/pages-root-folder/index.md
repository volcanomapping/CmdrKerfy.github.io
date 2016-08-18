---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: colorheader2.jpg
widget1:
  title: "What is OpenStreetMap?"
  url: 'http://www.openstreetmap.org/'
  image: osm_thumb.png
  text: 'An openly licensed map of the world created and maintained by volunteers using local knowledge, and remote mapping techniques. Click "More" to be redirected to OpenStreetMap.'
widget2:
  title: "The Project"
  url: 'https://volcanomapping.github.io/project/'
  image: puzzle_thumb.png
  text: 'Find out the impact missing infrastructure data has on humanitarian responses.'
widget3:
  title: "Current Task"
  url: 'https://volcanomapping.github.io/current/'
  text: 'Click "More" to find out how which volcano is currently being mapped.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="/images/usgs_thumb.png" width="302" height="182" alt=""/></a>'
  
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://volcanomapping.github.io/collaboration/ongoing/
  text: CLICK HERE TO SEE THE ONGOING WORK ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/mcvhKpKDD40" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
