---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "header_about_lmb.jpg"
widget1:
  title: "Getting Started"
  url: 'http://domain.de/must-be-absolut-url-like-this-one/'
  image: 'http://i.imgur.com/dl8mbVg.png'
  text: 'So what is this all about? Get started from here.'
widget2:
  title: "YouTube"
  url: 'https://www.youtube.com/channel/UCN1LkjECeRHBfQPSlqnCwOw'
  image: 'http://i.imgur.com/LnXcZ34.png'
  text: 'Check out my YouTube channel for more content and lots of information!'
widget3:
  title: "My Future Goals..."
  url: 'http://domain.de/must-be-absolut-url-like-this-one/'
  image: 'http://dummyimage.com/302x183/334d5c/efc94c.png&text=Placeholder'
  text: 'Sometimes you need to write down your goals in order to visualize them. Here are mine!'
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
  url: http://eepurl.com/ciwuGf
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
---
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
