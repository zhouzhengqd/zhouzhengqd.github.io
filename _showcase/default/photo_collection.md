---
show: true
width: 4
date: 2025-06-10 00:01:00 +0800
height: 295px
images:
- src: assets/images/etc/hainan.jpg
  # title: Photo 1
  # desc: Description 1.
  # link: https://picsum.photos/
- src: assets/images/etc/underwater.jpg
#   title: Photo 2
#   desc: Description 2
# - src: https://picsum.photos/seed/third33/800/800
- src: assets/images/etc/tibet1.png
#   title: Photo 2
#   desc: Description 2
# - src: https://picsum.photos/seed/third33/800/800
- src: assets/images/etc/tibet2.png
#   title: Photo 2
#   desc: Description 2
# - src: https://picsum.photos/seed/third33/800/800
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
