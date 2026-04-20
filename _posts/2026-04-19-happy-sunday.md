---
layout: post
title:  "好吃早餐午餐、趣味的下午時光"
author: l2l
categories: [桃園]
tags: [蜂蜜奶油麻糬吐司, 港式料理, 孔雀餅乾, 小美冰淇淋]
image: assets/images/20260419_draw4.png
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


<style>
.carousel {
  width: 500px;
  aspect-ratio: 16 / 9;
  position: relative;
  overflow: hidden;
  margin: auto;
  border-radius: 12px;
  background: #000;
}

.carousel img {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100%;
  height: 100%;
  transform: translate(-50%, -50%);
  object-fit: contain;
  opacity: 0;
  animation: fade 12.5s infinite;
}

.carousel img:nth-child(1) { animation-delay: 0s; }
.carousel img:nth-child(2) { animation-delay: 2.5s; }
.carousel img:nth-child(3) { animation-delay: 5s; }
.carousel img:nth-child(4) { animation-delay: 7.5s; }
.carousel img:nth-child(5) { animation-delay: 10s; }

@keyframes fade {
  0%   { opacity: 0; }
  4%   { opacity: 1; }
  20%  { opacity: 1; }
  24%  { opacity: 0; }
  100% { opacity: 0; }
}
</style>


今天一早，寶喝了我準備的養護膝蓋能量雞湯，我則吃著她親手做的蜂蜜奶油麻糬吐司當早餐，真的很好吃。

<center>
    <img src="./../../assets/images/20260419_breakfast.jpg">
</center>


午餐我們去吃港式料理，也同樣很滿足。花生醬吐司搭配奶油的鹹甜口感，再配上濃郁的花生飲品，以及特別的檸檬鹽味可樂，整體味道很有記憶點。

<div style="display: flex; justify-content: center; gap: 12px; align-items: center;">
    <img src="./../../assets/images/20260419_hk_drink.jpg" 
         style="width: 30%; height: auto; object-fit: cover; border-radius: 8px;">
    <img src="./../../assets/images/20260419_hk_toast.jpg" 
         style="width: 30%; height: auto; object-fit: cover; border-radius: 8px;">
</div>

下午我們一起玩了趣味版的你畫我猜，過程很歡樂（[點擊看原片](https://www.instagram.com/reels/DXRj9VQEhqK/)），下面是我們畫的 XDDD。

<center>
  <div class="carousel">
    <img src="./../../assets/images/20260419_draw.jpg">
    <img src="./../../assets/images/20260419_draw2.jpg">
    <img src="./../../assets/images/20260419_draw3.jpg">
    <img src="./../../assets/images/20260419_draw4.jpg">
    <img src="./../../assets/images/20260419_draw5.jpg">
  </div>
</center>

最後我們吃了孔雀餅乾冰淇淋和新出的小美冰淇淋口味，結果意外覺得小美反而更好吃，哈哈。

<center>
  <img src="./../../assets/images/20260419_hk_ice_cream.jpg">
</center>

<br>

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3616.2664563635453!2d121.30615322468758!3d24.99106032054271!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34681efd2574a111%3A0xcb67db3b225f2c72!2z576O55Sf6aSQ5a6kIOahg-WckuS4reiPr-W6l--8iOahg-Wckua4r-W8j-mjsuiMtuaOqOiWpu-8j-ahg-WckuWNgOa4r-W8j-m7nuW_g-S4i-WNiOiMtu-8j-ahg-WckuW_heWQg-e-jumjn-iBmumkkOmkkOW7s--8iQ!5e0!3m2!1szh-TW!2stw!4v1776695278721!5m2!1szh-TW!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
