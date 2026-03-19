---
layout: post
title:  "一起做火鍋、吃居酒屋、剪頭髮"
author: l2l
categories: [Taoyuan, New Taipei]
tags: [早午餐, 蜜糖吐司, 美術館, 三峽老街, 居酒屋, 做火鍋, 剪頭髮]
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

---

在 14 號這一天，我們一早就集合，先去吃了一頓超滿足的早午餐。前面其實就已經吃到快撐不住了，沒想到最後還加點了蜜糖吐司，於是我們只能挺著圓滾滾的肚子，一邊痛苦一邊享受地把它吃完，現在回想起來還是覺得很好笑。

<style>
/* ===== Carousel 容器 ===== */
.carousel {
  width: 500px;
  aspect-ratio: 16 / 9;
  position: relative;
  overflow: hidden;
  margin: auto;
  border-radius: 12px;
  background: #000;
}

/* ===== Carousel 內的圖片 ===== */
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

/* 每張圖片延遲時間 (5 張示例，每張停 2.5s) */
.carousel img:nth-child(1) { animation-delay: 0s; }
.carousel img:nth-child(2) { animation-delay: 2.5s; }
.carousel img:nth-child(3) { animation-delay: 5s; }
.carousel img:nth-child(4) { animation-delay: 7.5s; }
.carousel img:nth-child(5) { animation-delay: 10s; }

/* ===== 漸變動畫 ===== */
@keyframes fade {
  0%   { opacity: 0; }
  4%   { opacity: 1; }
  20%  { opacity: 1; }
  24%  { opacity: 0; }
  100% { opacity: 0; }
}
</style>

<!-- ===== Brunch Carousel ===== -->
<center>
  <div class="carousel">
    <img src="./../../assets/images/20260314_brunch_toast.jpg" alt="蜜糖吐司">
    <img src="./../../assets/images/20260314_brunch_noodle.jpg" alt="早午餐麵">
    <img src="./../../assets/images/20260314_brunch_rice.jpg" alt="早午餐飯">
    <img src="./../../assets/images/20260314_brunch_drink.jpg" alt="飲料">
    <img src="./../../assets/images/20260314_brunch_soup.jpg" alt="湯品">
  </div>
</center>

<br>

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3618.2207247447454!2d121.27956757606911!3d24.924549542688634!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x346819bb3daa47cf%3A0x9a3522e15677ee48!2zTW9tZW50IOaZguWIu-WSluWVoeWFq-W-t-W6l--8iOicnOezluWQkOWPuOOAgee-qeW8j-aWmeeQhuOAgee-juW8j-WltuaYlOWwiOizo--8iQ!5e0!3m2!1sen!2stw!4v1773928512286!5m2!1sen!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

<br>

接著，我們前往新北美術館，看了所謂的「石頭與棉線」展覽。老實說，有些藝術真的讓人一頭霧水（笑），但也算是一種特別的體驗。

<center>
<img src="./../../assets/images/20260314_museum.jpg" alt="美術館展覽">
</center>

之後我們轉戰三峽老街，邊走邊逛，還順道去了附近的農會晃晃。你還買了我最愛的甘草橄欖給我，真的很好吃，也讓這段行程多了一點小確幸。  
最後來到晚餐時間，我們一起去吃了一間居酒屋。雖然有點小踩雷，但反而也成了今天的一個有趣記憶（笑）。

<!-- ===== Izakaya Carousel ===== -->
<center>
  <div class="carousel">
    <img src="./../../assets/images/20260314_Izakaya_sashimi.jpg" alt="刺身">
    <img src="./../../assets/images/20260314_Izakaya_egg_rice.jpg" alt="蛋包飯">
    <img src="./../../assets/images/20260314_Izakaya_beef.jpg" alt="牛肉">
    <img src="./../../assets/images/20260314_Izakaya_yam.jpg" alt="山藥">
    <img src="./../../assets/images/20260314_Izakaya_bbq.jpg" alt="串燒">
  </div>
</center>

<br>

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3615.8511210705697!2d121.29772197607099!3d25.005174339450292!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34681f2882e596b1%3A0x8c2ccddebe0e646f!2z5pet6IuR5bGF6YWS5bGLIOWkp-ecvumFkuWgtA!5e0!3m2!1szh-TW!2stw!4v1773928863752!5m2!1szh-TW!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

---

到了隔天一早，也就是 15 號，我們一起動手做了一鍋超美味的火鍋，吃得飽飽又滿足。  
吃完之後，我們就開始今天的約會行程，到處逛街、隨意走走。

<!-- ===== Hotpot Carousel ===== -->
<center>
    <img src="./../../assets/images/20260315_hotpot.jpg" alt="火鍋">
</center>

騎車的過程更是充滿插曲，我們一路迷路、繞圈圈，完全沒有在按計畫走，反而變成最有趣的一段回憶，真的笑到不行。

最後，我們一起去剪了頭髮，寶直接大變身，變成氣質滿分的美少女，真的有夠驚艷（笑）。

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d17782.58052409306!2d121.31600236409213!3d24.965296319810342!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x34681f54363b72e7%3A0x86471255865687f7!2zUGlrb-a3seWknOa0l-mrruaymem-jS_liarpq64v54eZ6auuL-afk-mrrg!5e0!3m2!1sen!2stw!4v1773929355225!5m2!1sen!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
