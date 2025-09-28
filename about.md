---
layout: page
title: About Us
---

<p class="message">
  B&P Technology Co., Ltd., founded in 2025, is an integrator and supplier of quantum information technology, providing customized product solutions for clients worldwide.

</p>

Certifications:

<div class="image-row">
  <img src="{{ '/public/CHN.png' | absolute_url }}" alt="中文授权书">
  <img src="{{ '/public/EN.png' | absolute_url }}" alt="英文授权书">
  <img src="{{ '/public/Cer.jpg' | absolute_url }}" alt="营业执照">
</div>

<style>
.compact-image-row {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin: 20px 0;
  flex-wrap: nowrap; /* 确保严格在一排 */
  align-items: flex-start;
}

.compact-image-container {
  flex: 1;
  max-width: 200px; /* 控制最大宽度 */
  text-align: center;
}

.compact-image-container img {
  width: 100%;
  height: 150px; /* 较小的高度 */
  object-fit: contain;
  border-radius: 6px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  background-color: #f8f9fa;
  padding: 8px;
  transition: all 0.3s ease;
}

.compact-image-container img:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.compact-caption {
  margin-top: 8px;
  font-size: 14px;
  color: #333;
  font-weight: 500;
  line-height: 1.3;
}

/* 平板适配 */
@media (max-width: 768px) {
  .compact-image-row {
    gap: 10px;
  }
  .compact-image-container {
    max-width: 180px;
  }
  .compact-image-container img {
    height: 120px;
  }
  .compact-caption {
    font-size: 13px;
  }
}

/* 小屏手机强制保持一排 */
@media (max-width: 480px) {
  .compact-image-row {
    gap: 8px;
    flex-wrap: nowrap; /* 强制不换行 */
    overflow-x: auto; /* 如果太窄可以横向滚动 */
  }
  .compact-image-container {
    max-width: 150px;
    min-width: 120px; /* 设置最小宽度 */
  }
  .compact-image-container img {
    height: 100px;
  }
  .compact-caption {
    font-size: 12px;
  }
}
</style>
