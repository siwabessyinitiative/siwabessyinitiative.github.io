---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
# header:
#   image_fullwidth: layout-front.jpg

widget1:
  title: "Mengapa?"
  image: rsggas-302x182.png
  text: 'Kami meyakini bahwa teknologi nuklir akan membantu meningkatkan kesejahteraan masyarakat Indonesia melalui penyediaan lapangan kerja, sumber energi bersih, dan peningkatan kompetensi sumber daya manusia di Indonesia'
widget2:
  title: "Siapa?"
  image: dpr-302x182.png
  text: 'Kami adalah organisasi think-tank di bidang teknologi nuklir di Indonesia. Kami adalah mahasiswa, praktisi, dan peneliti nuklir yang punya perhatian terhadap perkembangan energi nuklir di Indonesia'
widget3:
  title: "Apa?"
  image: cooling-302x182.png  
  text: 'Kami ingin mendorong peran teknologi nuklir baik untuk energi maupun non-energi di Indonesia.'
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
  url: '/tentang-kami/'
  text: Pelajari lebih lanjut ›
  style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

