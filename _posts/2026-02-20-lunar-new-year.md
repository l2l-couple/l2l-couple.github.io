---
layout: post
title:  "2026 農曆年放煙火"
author: l2l
categories: [Taoyuan]
tags: [農曆新年, 放煙火]
image: assets/images/20260220_Fireworks.png
---


<audio id="bgm" loop preload="auto">
  <source src="/assets/music/20260220_NewYearFestival.mp3" type="audio/mpeg">
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

農曆新年到來，在初四這一天，我們一起迎著夜色施放璀璨的煙火。火光在空中綻放的瞬間，彷彿把一整年的祝福都點亮了。過程中雖然出現了一點小插曲 —— 鞭炮亂竄，差點被波及到，讓人忍不住驚呼又大笑，但也正因為這樣的不完美，反而讓回憶更加真實、有趣。

在煙火與笑聲交織的夜晚，妳手拿仙女棒，微微揮動，細碎的光點在你身旁閃爍。那一刻，妳的笑容比煙火還要溫柔，也比夜色更加明亮。我偷偷把這畫面收藏在心裡，也附上一張你玩仙女棒的可愛照片，紀念這個屬於我們、溫暖又浪漫的新年時刻。

<center>
  <img src="./../../assets/images/20260220_Fireworks-RuiChiu.jpg" style="width: 60%; height: auto;">
</center>


<br>

**希望未來我們能像剛剛仙女棒的火花一樣，不張揚、卻溫柔地一起微微放閃。也在彼此身邊，慢慢照亮對方的世界 💕**
