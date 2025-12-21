---
layout: page
title: 關於此網站
permalink: /about
comments: true
---

<div class="row justify-content-between">
<div class="col-md-8 pr-5">


<audio id="bgm" loop preload="auto">
  <source src="/assets/music/about.mp3" type="audio/mpeg">
</audio>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const audio = document.getElementById('bgm');

  audio.volume = 0.10;

  if (localStorage.getItem('allowMusic') === 'yes') {
    audio.play().catch(() => {});
  }

  const unlock = () => {
    audio.play().catch(() => {});
    localStorage.setItem('allowMusic', 'yes');
    document.removeEventListener('click', unlock);
    document.removeEventListener('touchstart', unlock);
  };

  document.addEventListener('click', unlock);
  document.addEventListener('touchstart', unlock);
});
</script>

<p>一個記錄我們日常與心動瞬間的情侶部落格<br>平凡的日子裡，一起慢慢寫下屬於我們的故事</p>

<p class="mb-5"><img class="shadow-lg" src="{{site.baseurl}}/assets/images/avatar.jpg" alt="無尾熊與尤加利樹" /></p>


</div>
</div>
