---
title: "生活照片"
excerpt: "相簿<br/><img src='/images/life/P2200113.jpg'>"
collection: portfolio
date: 2025-08-18
---

<div class="photo-grid">
  <img src="/images/life/P2200099.jpg">
  <img src="/images/life/P2200113.jpg">
  <img src="/images/life/P2200115.jpg">
  <img src="/images/life/P2200121.jpg">
  <img src="/images/life/P2200124.jpg">
  <img src="/images/life/P2200130.jpg">
  <img src="/images/life/P2200137.jpg">
  <img src="/images/life/P2210251.jpg">
  <img src="/images/life/P2210258.jpg">
</div>

<style>
.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 15px;
  padding: 20px 0;
}
.photo-grid img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  border-radius: 5px;
  cursor: pointer;
  transition: transform 0.2s;
}
.photo-grid img:hover {
  transform: scale(1.02);
}
</style>
