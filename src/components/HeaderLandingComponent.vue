<template>
  <div class="header-landing">
    <div class="header-nav logo special">
      <img class="header-logo" src="@/assets/images/logo.png" />
    </div>
    <div class="header-nav">
      <div><a href="#" target="_blank">О компании Smeg</a></div>
    </div>
    <div class="header-nav">
      <div><a href="#" target="_blank">Коллекции</a></div>
    </div>
    <div class="header-nav">
      <div><a href="#" target="_blank">Доставка</a></div>
    </div>
    <div class="header-nav">
      <div><a href="#" target="_blank">Сервис</a></div>
    </div>
    <div class="header-nav">
      <div><a href="#" target="_blank">Дизайнерам</a></div>
    </div>
    <div class="header-nav">
      <div><a href="#" target="_blank">Программа лояльности</a></div>
    </div>
    <div class="header-icons">
      <img src="@/assets/images/email_black_24dp.svg" />
      <img src="@/assets/images/phone_black_24dp.svg" />
    </div>
  </div>
</template>

<style scoped>
.header-landing {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.special {
  display: flex;
}

.header-nav a {
  padding: 8px;
}

@media (max-width: 965px) {
  .header-landing {
    flex-wrap: wrap;
    gap: 20px;
  }
  .special {
    width: 100%;
  }
  .header-icons {
    width: 100%;
    justify-content: center;
  }
}
.header-logo {
  height: 32px;
  width: auto;
}
.header-icons {
  display: flex;
  align-items: center;
  cursor: pointer;
}
.header-icons img:first-child {
  margin-right: 20px;
}
</style>
