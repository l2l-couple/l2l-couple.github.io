---
layout: post
title:  "一起手做蛋糕"
author: l2l
categories: [Taoyuan]
tags: [自己做, 手工蛋糕]
image: assets/images/20260301_Rui_Kevin.png
---



<audio id="bgm" loop preload="auto">
  <source src="/assets/music/20260301_Cake.mp3" type="audio/mpeg">
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


<p style="font-size: 12px; color: #888;">
  🎧 點擊畫面即可播放背景音樂
</p>





<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3615.628897268715!2d121.29922687607117!3d25.01272293914666!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34681fd09be81a99%3A0x8d2e3a39f1b6c1ce!2z6Ieq5bex5YGaIOeDmOeEmeiBmuaogumDqCDmoYPlnJLol53mloflupc!5e0!3m2!1szh-TW!2stw!4v1772608847457!5m2!1szh-TW!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
