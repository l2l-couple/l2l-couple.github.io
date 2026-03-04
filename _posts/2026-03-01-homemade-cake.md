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

<p style="font-size: 12px; color: #888;">🎧 點擊畫面即可播放背景音樂</p>

今天跟寶寶一起體驗製作手工蛋糕 🥰  
我們挑了**蘋果伯爵紅茶**口味，從一起備料、切配料，到慢慢組合、擠奶油，每一個小步驟都覺得好有趣 😌

<div class="card-container">
  <div class="card">
    <img src="./../../assets/images/20260301_Rui_Kevin_Cake.jpg">
  </div>
  <div class="card">
    <img src="./../../assets/images/20260301_Rui_Cream.jpg">
  </div>
</div>


<br>

看著妳專注又開心的樣子，我自己也覺得好溫暖 ❤️

最後一起把蛋糕拼盤完成時，那種「我們一起做成一件事」的感覺真的很棒，好像每次和妳一起的時光都能變成我們的甜蜜回憶 🥰

<div class="image-container">
  <img src="./../../assets/images/20260301_Cake.jpg" class="flash">
  <img src="./../../assets/images/20260301_Cake_Slice.jpg" class="flash">
</div>

<br>

以後還想跟寶寶一起做更多這種小事，把每一次小幸福都累積成我們的回憶 💛

<div style="text-align:center; margin-top:20px;">
  <img src="./../../assets/images/20260301_Cake_Rui.jpg">
</div>

<div style="text-align:center; margin-top:20px;">
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3615.628897268715!2d121.29922687607117!3d25.01272293914666!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34681fd09be81a99%3A0x8d2e3a39f1b6c1ce!2z6Ieq5bex5YGaIOeDmOeEmeiBmuaogumDqCDmoYPlnJLol53mloflupc!5e0!3m2!1szh-TW!2stw" width="600" height="450" style="border:0; max-width:100%;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>

<style>
.card-container {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}
.card {
  width: 150px;
  height: 150px;
  perspective: 1000px;
}
.card img {
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
  transform-style: preserve-3d;
  animation: rotateCard 3s infinite linear;
}
.card img:hover {
  animation-play-state: paused;
}

@keyframes rotateCard {
  0% { transform: rotateY(0deg); }
  50% { transform: rotateY(180deg); }
  100% { transform: rotateY(360deg); }
}

.image-container {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}
.flash {
  width: 150px;
  height: 150px;
  animation: flicker 1s linear 3;
}
.flash:hover {
  animation-play-state: paused;
}

@keyframes flicker {
  0%, 100% { opacity: 1; }
  25% { opacity: 0; }
  50% { opacity: 1; }
  75% { opacity: 0; }
}
</style>
