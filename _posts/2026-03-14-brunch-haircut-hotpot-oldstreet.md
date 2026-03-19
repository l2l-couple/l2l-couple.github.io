---
layout: post
title:  "一起做火鍋、吃居酒屋、剪頭髮"
author: l2l
categories: [Taoyuan, New Taipei]
tags: [早午餐, 蜜糖吐司, 三峽老街, 居酒屋, 做火鍋]
image: assets/images/20260314_haircut.png
---



<audio id="bgm" loop preload="auto">
  <source src="/assets/music/20260103-McDonladsBrunch.mp3" type="audio/mpeg">
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



