<template>
  <div class="main-content-landing">
    <div class="content-item content-landing-image">
        <img src="@/assets/images/prod_01.png" />
    </div>
    <div class="content-item">
      <div class="content-item-container">
          <div class="text-content-item">Сервис центр Hair в Москве и МО</div>
            <ul>
              <li>Экспресс диагностика в <span class="special">0 РУБ.</span></li>
              <li>Фирменная гарантия <span class="special">ДО 3Х ЛЕТ</span></li>
              <li>Срочный ремонт от <span class="special">40 МИНУТ</span></li>
              <li>Доставка в сервис центр курьером <span class="special">0 РУБ.</span></li>
              <li>Выезд мастера за 40 минут по Москве <span class="special">0 РУБ.</span></li>
            </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
.main-content-landing {
  display: flex;
  justify-content: space-between;
  align-items: end;
  gap: 100px;
  padding: 60px 0 60px 0;
}
.content-landing-image img {
  height: auto;
  width: 100%;
  aspect-ratio: 1.2;
  object-fit: cover;
}
.content-item {
  width: 50%;
}
.text-content-item {
  font-size: 48px;
  font-weight: 600;
  line-height: 1.2;
  padding-bottom: 20px;
}

.content-item-container ul li{
  list-style-type: none;
  line-height: 32px;
  padding: 8px 0 8px 0px;
}

.content-item-container li::before {
  content: ' ';
  background: transparent;
  border: 2px solid #000;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  display: block;
  position: absolute;
  top: 19px;
  left: -30px;
}

.content-item-container li span.special{
  color: #1636c9;
  font-weight: 700;
  font-size: 16px;
}

.content-item-container {
  padding: 30px 30px 50px 30px;
  background: #fff;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  border-radius: 6px;
  color: rgb(51, 51, 51);
  display: flex;
  flex-direction: column;
  justify-content: center;
}

@media (max-width: 1070px) {
  .main-content-landing {
    width: 100%;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }
  .content-item {
    width: 100%;
  }
  .content-item.content-landing-image {
    padding: 0 160px 0 160px;
  }
  .text-content-item  {
    font-size: 32px;
  }
}

@media (max-width: 745px) { 
  .content-item.content-landing-image {
    padding: 0 60px 0 60px;
  }
  .text-content-item  {
    font-size: 22px;
  }
}

</style>
