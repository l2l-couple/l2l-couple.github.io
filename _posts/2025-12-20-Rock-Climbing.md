---
layout: post
title:  "攀岩日"
author: l2l
categories: [Taoyuan]
tags: [攀岩、早午餐]
image: assets/images/20251220-rock-climbing.jpg
---


<audio id="bgm" loop preload="auto">
  <source src="/assets/music/20251220-Rock-Climbing.mp3" type="audio/mpeg">
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


這天的情侶日誌記錄著一段輕快又充實的行程。早上，他們先到吾食享用可頌麵包早午餐，外酥內軟的可頌配上溫熱的飲品，為一天揭開香氣四溢的序幕。補足能量後，兩人前往[Passion 攀岩館](https://maps.app.goo.gl/YRwoy9VbSgXuAk2D7)，在一條條路線前彼此加油、輪流挑戰，汗水與笑聲交織成默契。從早餐的悠閒到攀岩的專注，這一天把平凡的時光攀成了難忘的高度。

<center>
  <img src="./../../assets/images/20251220-brunch.jpg">
</center>
<br>
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3615.6727841268703!2d121.29174747609201!3d25.01123233920659!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34681feac93af1dd%3A0x1643fdde6522214c!2z5ZC-6aOfT3VyIEJydW5jaA!5e0!3m2!1szh-TW!2stw!4v1766326448982!5m2!1szh-TW!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
