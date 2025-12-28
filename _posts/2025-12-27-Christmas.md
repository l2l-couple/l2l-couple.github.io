---
layout: post
title:  "聖誕節"
author: l2l
categories: [Taipei]
tags: [聖誕節, 冰上溜冰]
image: assets/images/20251227-gift.jpg
---



<audio id="bgm" loop preload="auto">
  <source src="/assets/music/20251227-christmas.mp3" type="audio/mpeg">
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

寒冷的冬天，我用我溫暖的雙手牽著妳細嫩的手走在光滑的冰面上


<table border="0" cellpadding="10">
  <tr>
    <td>
      <img src="./../../assets/images/20251227-hand.jpg" width="200">
    </td>
    <td>
      <img src="./../../assets/images/20251227-skate.png" width="200">
    </td>
  </tr>
</table>

<img src="./../../assets/images/20251227-cream.jpg" width="400">

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3614.4980401810544!2d121.54790367609269!3d25.051103437601174!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3442abe81eb85771%3A0xca7679816a73f5cd!2z6Ie65YyX5bCP5beo6JuL5Yaw5LiK5qiC5ZyS!5e0!3m2!1szh-TW!2stw!4v1766938529286!5m2!1szh-TW!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
