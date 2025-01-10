---
layout: page
title: people
permalink: /people/
description:
nav: true
nav_order: 2
---

<style>
  :root {
    --card-height: 140px; /* 控制每个卡片的高度 */
  }

  .person-card {
    width: 45%; /* 每行2个卡片，设置每个卡片占据父容器的45% */
    height: var(--card-height); /* 使用全局变量控制高度 */
    display: flex;
    flex-direction: row; /* 水平排列，图片和文本并排显示 */
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 10px;
    margin-bottom: 20px;
    overflow: hidden;
  }

  .person-card img {
    width: 100px; /* 设置图片的宽度 */
    height: 100px; /* 设置图片的高度 */
    object-fit: cover;
    border-radius: 4px;
    margin-right: 10px; /* 图片和文本之间的间距 */
  }

  .person-card .text {
    flex: 1; /* 让文本部分占据剩余空间 */
  }

  .person-card h3 {
    margin: 0;
    font-size: 18px;
    font-weight: bold;
  }

  .person-card .line {
    height: 1px;
    background-color: #ddd;
    margin: 10px 0;
  }

  .person-card .research,
  .person-card .email {
    font-size: 14px;
    margin-bottom: 5px;
  }

  .category {
    margin-bottom: 30px;
  }

  .category h2 {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
  }

  .category .people-container {
    display: flex;
    flex-wrap: wrap; /* 允许卡片换行 */
    gap: 20px; /* 卡片之间的间距 */
  }
</style>

<div class="category">
  <h2>Principal Investigators</h2>
  <div class="people-container">
    <!-- Person 1 -->
    <div class="person-card">
      <img src="/assets/img/4.jpg" alt="Albert Einstein">
      <div class="text">
        <h3>Dr. Albert Einstein</h3>
        <div class="line"></div>
        <div class="research">Theory of Relativity</div>
        <div class="email">einstein@university.edu</div>
      </div>
    </div>

    <!-- Person 2 -->
    <div class="person-card">
      <img src="/assets/img/4.jpg" alt="Isaac Newton">
      <div class="text">
        <h3>Dr. Isaac Newton</h3>
        <div class="line"></div>
        <div class="research">Laws of Motion and Gravity</div>
        <div class="email">newton@university.edu</div>
      </div>
    </div>

    <!-- Person 3 -->
    <div class="person-card">
      <img src="/assets/img/4.jpg" alt="Marie Curie">
      <div class="text">
        <h3>Dr. Marie Curie</h3>
        <div class="line"></div>
        <div class="research">Radioactivity</div>
        <div class="email">curie@university.edu</div>
      </div>
    </div>
  </div>
</div>

<div class="category">
  <h2>PhD Students</h2>
  <div class="people-container">
    <!-- Person 1 -->
    <div class="person-card">
      <img src="/assets/img/4.jpg" alt="John Doe">
      <div class="text">
        <h3>John Doe</h3>
        <div class="line"></div>
        <div class="research">Deep Learning for NLP</div>
        <div class="email">johndoe@university.edu</div>
      </div>
    </div>

    <!-- Person 2 -->
    <div class="person-card">
      <img src="/assets/img/4.jpg" alt="Jane Smith">
      <div class="text">
        <h3>Jane Smith</h3>
        <div class="line"></div>
        <div class="research">Climate Change and Marine Ecosystems</div>
        <div class="email">janesmith@university.edu</div>
      </div>
    </div>

    <!-- Person 3 -->
    <div class="person-card">
      <img src="/assets/img/4.jpg" alt="Emily Johnson">
      <div class="text">
        <h3>Emily Johnson</h3>
        <div class="line"></div>
        <div class="research">Quantum Computing Algorithms</div>
        <div class="email">emilyjohnson@university.edu</div>
      </div>
    </div>
  </div>
</div>

<div class="category">
  <h2>Undergraduates</h2>
  <div class="people-container">
    <!-- Person 1 -->
    <div class="person-card">
      <img src="/assets/img/4.jpg" alt="Michael Lee">
      <div class="text">
        <h3>Michael Lee</h3>
        <div class="line"></div>
        <div class="research">AI in Computer Science</div>
        <div class="email">michaellee@university.edu</div>
      </div>
    </div>

    <!-- Person 2 -->
    <div class="person-card">
      <img src="/assets/img/4.jpg" alt="Alice Wong">
      <div class="text">
        <h3>Alice Wong</h3>
        <div class="line"></div>
        <div class="research">Renewable Energy Solutions</div>
        <div class="email">alicewong@university.edu</div>
      </div>
    </div>

    <!-- Person 3 -->
    <div class="person-card">
      <img src="/assets/img/4.jpg" alt="David Kim">
      <div class="text">
        <h3>David Kim</h3>
        <div class="line"></div>
        <div class="research">Machine Learning in Healthcare</div>
        <div class="email">davidkim@university.edu</div>
      </div>
    </div>
  </div>
</div>
