---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
=
I am currently pursuing a master’s degree at the School of Computer Science and Mathematics, Fujian University of Technology. I received my bachelor's degree in Software Engineering from Southwest Minzu University in 2021. My research focuses on applying deep learning to image and video processing, with particular interests in medical image tasks, industrial anomaly detection, and accident recognition.

![Photo 1](images/pic1.jpg)
![Photo 2](images/pic2.jpg)
![Photo 3](images/pic3.jpg)
![Photo 4](images/pic4.jpg)
![Photo 5](images/pic5.jpg)
![Photo 6](images/pic6.jpg)
![Photo 7](images/pic7.jpg)
![Photo 8](images/pic8.jpg)
![Photo 9](images/pic9.jpg)
![Photo 10](images/pic10.jpg)
![Photo 11](images/pic11.jpg)

<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->
<div class="empty-row"></div> <!-- 空行 -->

<link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />
<style>
  body {
    margin: 0;
    padding: 0;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }

  .swiper-container {
    width: 100%; /* 100% 宽度 */
    height: 100px; /* 固定高度 */
    background-color: #fff; /* 背景颜色 */
    box-shadow: 0 -2px 5px rgba(0,0,0,0.3); /* 可选的阴影效果 */
    overflow: hidden; /* 隐藏超出容器的部分 */
    margin: 20px 0; /* 设置上下外边距来创建空行 */
  }

  .swiper-wrapper {
    display: flex;
    flex-direction: row; /* 确保子元素横向排列 */
  }

  .swiper-slide {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100px; /* 固定每张图片的宽度 */
    height: 100%; /* 高度填满容器 */
    padding: 0; /* 移除内边距 */
    box-sizing: border-box; /* 包括内边距和边框在内 */
  }

  .swiper-slide img {
    width: 100%; /* 图片宽度填满 slide 容器 */
    height: 100%; /* 图片高度填满 slide 容器 */
    object-fit: cover; /* 保持图片比例，填充容器 */
    display: block;
  }

  .swiper-pagination-bullet {
    background: #000;
  }
  .swiper-button-next, .swiper-button-prev {
    color: #000;
  }
</style>

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
    loop: true, /* 启用循环模式 */
    slidesPerView: 7, /* 一次显示 7 张图片 */
    spaceBetween: 100, /* 图片之间的间隔 */
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
