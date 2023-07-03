<template>
  <div class="footer-landing">
    <div class="footer-item special">
      <img class="footer-logo" src="@/assets/images/logo.png" />
    </div>
    <div class="footer-item special">Ремонт техники</div>
    <div class="footer-item special">О сервисе</div>
    <div class="footer-item">
      <div class="phone-number">8 800 707-00-29</div>
      <button class="footer-btn">Обратный звонок</button>
    </div>
    <div class="footer-little">
    </div>
    <div class="footer-little-two">
    </div>
    <div class="footer-little-tree">
    </div>
    <div class="footer-little-four">
    </div>
  </div>
</template>

<style scoped>
.footer-landing {
  position: relative;
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
  height: 60px;
  width: auto;
}

.footer-btn {
  background: #0074BF;
  color: #fff;
  font-size: 16px;
  font-weight: 600;
  box-shadow: inset 0px 0px 15px 11px rgba(0, 0, 0, 0.25);
  border-radius: 60px;
  cursor: pointer;
  width: 235px;
  height: 60px;
  width: 100%;
  border: 0;
  padding: 0 40px 0 40px;
  white-space: nowrap;
  z-index: 3;
}

.footer-btn:hover {
  background: #5690f5;
}

.special {
  z-index: 4;
}

@media (max-width: 850px) {
  .footer-landing{
    flex-wrap: wrap;
    gap: 20px;
  }

  .footer-item {
    width: 100%;
  }
  .special {
    display: flex;
    justify-content: center;
    z-index: 4;
  }
}

.footer-little {
  background: transparent;
  opacity: 0.6;
  border: 1px solid #778899;
  width: 220px;
  height: 220px;
  border-radius: 50%;
  position: absolute;
  top: 49px;
  right: 50%;
  transform: translateX(100%);
  z-index: 2;
}

.footer-little-two {
  background: transparent;
  opacity: 0.6;
  border: 1px solid #778899;
  width: 192px;
  height: 192px;
  border-radius: 50%;
  position: absolute;
  top: 69px;
  right: 50%;
  transform: translateX(-50%);
  z-index: 1;
}

.footer-little-tree {
  background: transparent;
  opacity: 0.6;
  border: 1px solid #778899;
  width: 400px;
  height: 400px;
  border-radius: 50%;
  position: absolute;
  bottom: -300px;
  right: 50%;
  transform: translateX(-100px);
}
.footer-little-four {
  opacity: 0.8;
  background: rgba(41,137,216,1);
  border: none;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  position: absolute;
  top: 80px;
  right: 50%;
  transform: translateX(200px);
  animation: go-left-right 3s infinite;
  transform-origin: 30px 50px;
  z-index: 1;
}
@keyframes go-left-right {   
    from {transform: rotate(0) translateX(100px)}
    to {transform: rotate(360deg) translateX(100px)}     
    /* from { transform: translateX(-60px) translateY(-20px); }  
    50% { transform: translateX(10px) translateY(100px); } 
    to { transform: translateX(110px) trsanslateY(50px); }  */
  }

</style>
