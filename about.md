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
.image-row {
  display: flex;
  justify-content: space-between;
  gap: 15px;
  flex-wrap: wrap;
  margin: 30px 0;
  align-items: center;
}

.image-row img {
  flex: 1;
  min-width: 200px;
  max-width: 100%;
  height: 250px;
  object-fit: cover;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.image-row img:hover {
  transform: scale(1.05);
}

@media (max-width: 768px) {
  .image-row {
    flex-direction: column;
    gap: 20px;
  }
  .image-row img {
    width: 100%;
    max-width: 400px;
    height: 250px;
  }
}
</style>
