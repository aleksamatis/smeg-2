<template>
  <div class="header-landing">
    <div class="logo special">
      <img class="header-logo" src="@/assets/images/logo.png" />
    </div>
    <div class="header-icons">
      <img src="@/assets/images/email_black_24dp.svg" />
      <img src="@/assets/images/phone_black_24dp.svg" />
    </div>
    <div class="header-button">
      <button class="header-btn">Обратный звонок</button>
    </div>
  </div>
</template>

<style scoped>
.header-landing {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.header-landing div {
  width: 33%;
}
.special {
  display: flex;
}
.header-logo {
  height: 60px;
  width: auto;
}
.header-icons {
  display: flex;
  align-items: center;
  cursor: pointer;
  justify-content: center;
}
.header-button {
  display: flex;
  align-items: center;
  justify-content: end;
}
.header-icons img {
  margin-right: 20px;
}

.header-icons img:last-child {
  margin-right: 0;
}
.header-btn {
  background: #0074BF;
  color: #fff;
  font-size: 16px;
  font-weight: 600;
  box-shadow: inset 0px 0px 15px 11px rgba(0, 0, 0, 0.25);
  border-radius: 60px;
  cursor: pointer;
  width: 100%;
  height: 60px;
  max-width: 250px;
  border: 0;
  padding: 0 40px 0 40px;
  text-align: center;
}

.header-btn:hover {
  background: #5690f5;
}

@media screen and (max-width: 630px) {
  .header-landing {
    flex-direction: column;
    align-content: center;
    gap: 32px;
  }

  .header-landing div {
    width: auto;
  }
}
</style>
