---
layout: page
title: About Us
---

<p class="message">
  B&P Technology Co., Ltd., founded in 2025, is an integrator and supplier of quantum information technology, providing customized product solutions for clients worldwide.

</p>

Certifications:


<div class="image-row">
  <div class="image-container">
    <img src="{{ '/public/CHN.png' | absolute_url }}" alt="中文授权书">
    <p class="image-caption">中文授权书</p>
  </div>
  <div class="image-container">
    <img src="{{ '/public/EN.png' | absolute_url }}" alt="英文授权书">
    <p class="image-caption">英文授权书</p>
  </div>
  <div class="image-container">
    <img src="{{ '/public/Cer.jpg' | absolute_url }}" alt="营业执照">
    <p class="image-caption">营业执照</p>
  </div>
</div>

<style>
.image-row {
  display: flex;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
  margin: 40px 0;
  align-items: flex-start;
}

.image-container {
  flex: 1;
  min-width: 250px;
  text-align: center;
}

.image-container img {
  width: 100%;
  height: 300px; /* 固定高度保持一致性 */
  object-fit: contain; /* 保持图片完整比例 */
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  background-color: #f8f9fa; /* 白色背景图片的底色 */
  padding: 10px;
  transition: all 0.3s ease;
}

.image-container img:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}

.image-caption {
  margin-top: 12px;
  font-size: 16px;
  font-weight: 500;
  color: #333;
  line-height: 1.4;
}

/* 平板设备适配 */
@media (max-width: 1024px) {
  .image-container {
    min-width: 200px;
  }
  .image-container img {
    height: 250px;
  }
}

/* 移动端适配 */
@media (max-width: 768px) {
  .image-row {
    flex-direction: column;
    gap: 30px;
  }
  .image-container {
    width: 100%;
    max-width: 500px;
    margin: 0 auto;
  }
  .image-container img {
    height: 300px;
  }
}

/* 小屏手机适配 */
@media (max-width: 480px) {
  .image-container img {
    height: 250px;
  }
  .image-caption {
    font-size: 14px;
  }
}
</style>
