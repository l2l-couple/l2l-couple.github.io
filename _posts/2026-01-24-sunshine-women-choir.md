---
layout: post
title:  "第一次一起看電影"
author: l2l
categories: [Taoyuan]
tags: [陽光女子合唱團, 電影]
image: assets/images/20260124-unshine-women-choir.png
---


<audio id="bgm" loop preload="auto">
  <source src="/assets/music/20260124-unshine-women-choir.mp3" type="audio/mpeg">
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

今天和北鼻第一次看電影，她精心挑選了一部想讓我掉眼淚的影片。結果，我果然忍住流下眼淚，而身為「主嫌」的她也跟著不爭氣地掉淚，笑死我們。

我們看的是《陽光女子合唱團》，裡面的每個主角都有自己的背景故事，我也不由得看到我和北鼻過去經歷的影子。這部電影之所以好看，主要是因為它呈現了每個人不同的背景，但都展現出那份堅強的生命意志，真的很感人。

<center>
  <img src="./../../assets/images/20260124-movie-ticket.jpg" style="width: 60%; height: auto;">
</center>

<br>

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3616.267770835384!2d121.31006687609157!3d24.991015640019803!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34681efcc18ce42b%3A0xc35cb2a3230d61bc!2z57Wx6aCY5buj5aC0!5e0!3m2!1szh-TW!2stw!4v1769437881583!5m2!1szh-TW!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
