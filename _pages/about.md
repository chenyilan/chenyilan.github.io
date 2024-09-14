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
  body {
    margin: 0;
    padding: 0;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }

  .container {
    position: relative;
    width: 100%; /* 设置为 100% 以适应父容器宽度 */
    height: 100vh; /* 让容器占满视口高度 */
  }

  .swiper-container {
    width: 100%; /* 改为 100% 以适应父容器的宽度 */
    height: 90px; /* 根据需要调整 */
    background-color: #fff; /* 背景颜色 */
    box-shadow: 0 -2px 5px rgba(0,0,0,0.3); /* 可选的阴影效果 */
    position: absolute;
    bottom: 0; /* 使轮播位于容器底部 */
  }

  .swiper-slide {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%; /* 改为 100% 以适应容器的宽度 */
    padding: 0 10px; /* 图片之间的间隔 */
  }

  .swiper-slide img {
    width: 100%; /* 固定宽度 */
    height: 100%; /* 固定高度 */
    object-fit: cover; /* 保持图片比例，填充容器 */
    display: block;
  }

  .swiper-title {
    text-align: center;
    font-size: 24px;
    margin-bottom: 10px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    background-color: #fff; /* 背景颜色，确保标题背景不透明 */
    padding: 10px 0; /* 上下内边距 */
    box-shadow: 0 2px 5px rgba(0,0,0,0.3); /* 可选的阴影效果 */
  }

  .swiper-pagination-bullet {
    background: #000;
  }
  .swiper-button-next, .swiper-button-prev {
    color: #000;
  }
</style>

<div class="container">
  <div class="swiper-title">My Photo</div> <!-- 轮播的标题 -->
  <div class="swiper-container">
    <div class="swiper-wrapper">
      <div class="swiper-slide"><img src="images/pic1.jpg" alt="Photo 1" /></div>
      <div class="swiper-slide"><img src="images/pic2.jpg" alt="Photo 2" /></div>
      <div class="swiper-slide"><img src="images/pic3.jpg" alt="Photo 3" /></div>
      <div class="swiper-slide"><img src="images/pic4.jpg" alt="Photo 4" /></div>
      <div class="swiper-slide"><img src="images/pic5.jpg" alt="Photo 5" /></div>
      <div class="swiper-slide"><img src="images/pic6.jpg" alt="Photo 6" /></div>
      <div class="swiper-slide"><img src="images/pic7.jpg" alt="Photo 7" /></div>
      <div class="swiper-slide"><img src="images/pic8.jpg" alt="Photo 8" /></div>
      <div class="swiper-slide"><img src="images/pic9.jpg" alt="Photo 9" /></div>
      <div class="swiper-slide"><img src="images/pic10.jpg" alt="Photo 10" /></div>
      <div class="swiper-slide"><img src="images/pic11.jpg" alt="Photo 11" /></div>
      <!-- 添加更多的照片 -->
    </div>
    <!-- 添加分页器 -->
    <div class="swiper-pagination"></div>
    <!-- 添加导航按钮 -->
    <div class="swiper-button-next"></div>
    <div class="swiper-button-prev"></div>
  </div>
</div>

<!-- Swiper JS -->
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
<script>
  var swiper = new Swiper('.swiper-container', {
    direction: 'horizontal',
    loop: true,
    slidesPerView: 7, /* 一次显示 7 张图片 */
    spaceBetween: 10, /* 图片之间的间隔 */
    autoplay: {
      delay: 3000, // 自动滚动的时间间隔（以毫秒为单位）
    },
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
