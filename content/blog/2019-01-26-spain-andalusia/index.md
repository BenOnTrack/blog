---
title: Spain - Andalusia
author: BenOnTrack
date: '2019-01-26'
image: images/post/andalusia.jpg
type: post
gallery : 'test'
categories:
  - Europe
tags:
  - Video
---

We have decided to plan a small trip to Andalusia from 22nd to 27th of January as we've still never been in south of Spain.

Starting from Sevilla, we'll reach Grenada and Cordobá.

{{< youtube uQUGTgI9e7g >}}








<!-- The Gallery as inline carousel, can be positioned anywhere on the page -->
<div
  id="blueimp-gallery-carousel2"
  class="blueimp-gallery blueimp-gallery-carousel"
  aria-label="image carousel">
  <div class="slides" aria-live="off"></div>
  <h3 class="title"></h3>
  <a
    class="prev"
    aria-controls="blueimp-gallery-carousel"
    aria-label="previous slide"></a>
  <a
    class="next"
    aria-controls="blueimp-gallery-carousel"
    aria-label="next slide"></a>
  <a
    class="play-pause"
    aria-controls="blueimp-gallery-carousel"
    aria-label="play slideshow"
    aria-pressed="true"
    role="button"></a>
  <ol class="indicator"></ol>
</div>

<script src="/plugins/blueimp/blueimp-gallery.min.js"></script>



<div id="links2">
    <a href="/images/gallery/test/author.jpg"></a>
    <a href="/images/gallery/test/contact.jpg"></a>
</div>

<div>

  <script>
  document.getElementById('links2').onclick = function (event) {
    event = event || window.event
    var target = event.target || event.srcElement
    var link = target.src ? target.parentNode : target
    var options = { index: link, event: event }
    var links = this.getElementsByTagName('a')
    blueimp.Gallery(links, options)
  }
</script>

<script>
  blueimp.Gallery(document.getElementById('links2').getElementsByTagName('a'), {
    container: '#blueimp-gallery-carousel2',
    carousel: true
  })
</script>
  
</div>