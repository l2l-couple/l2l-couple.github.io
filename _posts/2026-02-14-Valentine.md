---
layout: post
title:  "第一次過情人節"
author: l2l
categories: [New Taipei]
tags: [情人節, 青焰炭火熟成牛排, Cremia 冰淇淋]
image: assets/images/20260214_SteakStore2.jpg
description: "第一次過情人節，我不太會說情話，但我會把妳放在心上。今天如此，以後也是。"
featured: true
hidden: true
rating: 4
---


<audio id="bgm" loop preload="auto">
  <source src="/assets/music/20260214_valentine.mp3" type="audio/mpeg">
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





<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3614.232800138903!2d121.45142017609297!3d25.060097537238832!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3442a9d3b90424ab%3A0x898efd93761a50e5!2z6Z2S54SwIOeCreeBq-eGn-aIkOeJm-aOkijmlrDojorlmInou5LploDluIIp!5e0!3m2!1szh-TW!2stw!4v1771082116525!5m2!1szh-TW!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
