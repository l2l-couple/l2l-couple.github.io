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

<center>
  <div class="carousel">
    <img src="./../../assets/images/20260314_brunch_toast.jpg">
    <img src="./../../assets/images/20260314_brunch_noodle.jpg">
    <img src="./../../assets/images/20260314_brunch_rice.jpg">
    <img src="./../../assets/images/20260314_brunch_drink.jpg">
    <img src="./../../assets/images/20260314_brunch_soup.jpg">
  </div>
</center>

<br>

<center>
<img src="./../../assets/images/20260314_museum.jpg">
</center>

<center>
  <div class="carousel">
    <img src="./../../assets/images/20260314_Izakaya_sashimi.jpg">
    <img src="./../../assets/images/20260314_Izakaya_egg_rice.jpg">
    <img src="./../../assets/images/20260314_Izakaya_beef.jpg">
    <img src="./../../assets/images/20260314_Izakaya_yam.jpg">
    <img src="./../../assets/images/20260314_Izakaya_bbq.jpg">
  </div>
</center>

<br>

<center>
    <img src="./../../assets/images/20260315_hotpot.jpg">
</center>
