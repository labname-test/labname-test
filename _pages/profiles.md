---
layout: page
title: people
permalink: /people/
description:
nav: true
nav_order: 1
---

<style>
  :root {
    --card-height: 300px; /* 你可以根据需要调整高度 */
  }
  
  .person-card {
    width: 200px; /* 方框宽度 */
    height: var(--card-height); /* 使用全局变量控制高度 */
    display: flex;
    flex-direction: column;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 10px;
    overflow: hidden;
  }

  .person-card img {
    width: 100%;
    height: 100px; /* 方形图片 */
    object-fit: cover;
    border-radius: 4px;
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

  .person-card .research {
    font-size: 14px;
    font-weight: normal;
    margin-bottom: 5px;
  }

  .person-card .email {
    font-size: 14px;
    color: #555;
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
    justify-content: space-between;
    gap: 20px;
    flex-wrap: wrap;
  }
</style>

<div class="category">
  <h2>Principal Investigators</h2>
  <div class="people-container">
    <!-- Person 1 -->
    <div class="person-card">
      <h3>Dr. Albert Einstein</h3>
      <div class="line"></div>
      <img src="/assets/img/4.jpg" alt="Albert Einstein">
      <div class="research">Theory of Relativity</div>
      <div class="email">einstein@university.edu</div>
    </div>

    <!-- Person 2 -->
    <div class="person-card">
      <h3>Dr. Isaac Newton</h3>
      <div class="line"></div>
      <img src="/assets/img/4.jpg" alt="Isaac Newton">
      <div class="research">Laws of Motion and Gravity</div>
      <div class="email">newton@university.edu</div>
    </div>

    <!-- Person 3 -->
    <div class="person-card">
      <h3>Dr. Marie Curie</h3>
      <div class="line"></div>
      <img src="/assets/img/4.jpg" alt="Marie Curie">
      <div class="research">Radioactivity</div>
      <div class="email">curie@university.edu</div>
    </div>
  </div>
</div>

<div class="category">
  <h2>PhD Students</h2>
  <div class="people-container">
    <!-- Person 1 -->
    <div class="person-card">
      <h3>John Doe</h3>
      <div class="line"></div>
      <img src="/assets/img/4.jpg" alt="John Doe">
      <div class="research">Deep Learning for NLP</div>
      <div class="email">johndoe@university.edu</div>
    </div>

    <!-- Person 2 -->
    <div class="person-card">
      <h3>Jane Smith</h3>
      <div class="line"></div>
      <img src="/assets/img/4.jpg" alt="Jane Smith">
      <div class="research">Climate Change and Marine Ecosystems</div>
      <div class="email">janesmith@university.edu</div>
    </div>

    <!-- Person 3 -->
    <div class="person-card">
      <h3>Emily Johnson</h3>
      <div class="line"></div>
      <img src="/assets/img/4.jpg" alt="Emily Johnson">
      <div class="research">Quantum Computing Algorithms</div>
      <div class="email">emilyjohnson@university.edu</div>
    </div>
  </div>
</div>

<div class="category">
  <h2>Undergraduates</h2>
  <div class="people-container">
    <!-- Person 1 -->
    <div class="person-card">
      <h3>Michael Lee</h3>
      <div class="line"></div>
      <img src="/assets/img/4.jpg" alt="Michael Lee">
      <div class="research">AI in Computer Science</div>
      <div class="email">michaellee@university.edu</div>
    </div>

    <!-- Person 2 -->
    <div class="person-card">
      <h3>Alice Wong</h3>
      <div class="line"></div>
      <img src="/assets/img/4.jpg" alt="Alice Wong">
      <div class="research">Renewable Energy Solutions</div>
      <div class="email">alicewong@university.edu</div>
    </div>

    <!-- Person 3 -->
    <div class="person-card">
      <h3>David Kim</h3>
      <div class="line"></div>
      <img src="/assets/img/4.jpg" alt="David Kim">
      <div class="research">Machine Learning in Healthcare</div>
      <div class="email">davidkim@university.edu</div>
    </div>
  </div>
</div>
