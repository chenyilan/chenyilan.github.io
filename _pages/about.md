---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently pursuing a master’s degree at the School of Computer Science and Mathematics, Fujian University of Technology. I received my bachelor's degree in Software Engineering from Southwest Minzu University in 2021. My research focuses on applying deep learning to image and video processing, with particular interests in medical image tasks, industrial anomaly detection, and accident recognition.
<link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />
<style>
  .swiper-container {
    width: 100%;
    height: 300px; /* 根据需要调整 */
    position: relative;
  }

  .swiper-slide {
    display: flex;
    justify-content: center;
    align-items: center;
    width: auto;
    padding: 0 10px; /* 图片之间的间隔 */
  }

  .swiper-slide img {
    width: 100%;
    height: auto;
    display: block;
  }

  .swiper-title {
    text-align: center;
    font-size: 24px;
    margin-bottom: 10px;
  }

  /* Optional: Style pagination and navigation buttons */
  .swiper-pagination-bullet {
    background: #000;
  }
  .swiper-button-next, .swiper-button-prev {
    color: #000;
  }
</style>

<div class="swiper-container">
  <div class="swiper-title">My Photo Gallery</div> <!-- 轮播的标题 -->
  <div class="swiper-wrapper">
    <div class="swiper-slide"><img src="images/bio-photo-2.jpg" alt="Photo 1" /></div>
    <div class="swiper-slide"><img src="images/bio-photo-2.jpg" alt="Photo 2" /></div>
    <div class="swiper-slide"><img src="images/bio-photo-2.jpg" alt="Photo 3" /></div>
    <div class="swiper-slide"><img src="images/bio-photo-2.jpg" alt="Photo 4" /></div>
    <div class="swiper-slide"><img src="images/bio-photo-2.jpg" alt="Photo 5" /></div>
    <div class="swiper-slide"><img src="images/bio-photo-2.jpg" alt="Photo 6" /></div>
    <!-- 添加更多的照片 -->
  </div>
  <!-- 添加分页器 -->
  <div class="swiper-pagination"></div>
  <!-- 添加导航按钮 -->
  <div class="swiper-button-next"></div>
  <div class="swiper-button-prev"></div>
</div>

<!-- Swiper JS -->
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
<script>
  var swiper = new Swiper('.swiper-container', {
    direction: 'horizontal',
    loop: true,
    pagination: {
      el: '.swiper-pagination',
      clickable: true,
    },
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
  });
</script>
