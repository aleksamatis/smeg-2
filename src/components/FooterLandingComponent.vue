<template>
  <div class="footer-landing">
    <div class="footer-item special">
      <img class="footer-logo" src="@/assets/images/logo.png" />
    </div>
    <div class="footer-item special">Официальный магазин Smeg в России</div>
    <div class="footer-item">
      <div class="phone-number">8 800 707-00-29</div>
      <button class="footer-btn">Обратный звонок</button>
    </div>
  </div>
</template>

<style scoped>
.footer-landing {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-top: 60px;
}

.footer-item {
  width: 30%;
}
.footer-item .phone-number{
  text-align: center;
  font-weight: 600;
  padding-bottom: 15px;
}

.footer-logo {
  height: 32px;
  width: auto;
}

.footer-btn {
  background: #6b1a39;
  color: #fff;
  font-size: 14px;
  box-shadow: inset 0px 0px 15px 11px rgba(0, 0, 0, 0.25);
  border-radius: 60px;
  cursor: pointer;
  width: 235px;
  height: 60px;
  width: 100%;
  border: 0;
  padding: 0 40px 0 40px;
  white-space: nowrap;
}

.footer-btn:hover {
  background: #7e2e4a;
}

@media (max-width: 850px) {
  .footer-landing{
    flex-wrap: wrap;
    gap: 20px;
  }

  .footer-item {
    width: 100%;
  }
}
</style>
