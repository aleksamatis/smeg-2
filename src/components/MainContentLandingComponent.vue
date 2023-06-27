<template>
  <div class="main-content-landing">
    <div class="content-item">
      <div class="content-item-container">
        <img src="@/assets/images/category_hob.jpg" />
        <div class="text-content-item">Вытяжки</div>
      </div>
    </div>
    <div class="content-item">
      <div class="content-item-container">
        <img src="@/assets/images/category_sinks.jpg" />
        <div class="text-content-item">Мойки</div>
      </div>
    </div>
    <div class="content-item">
      <div class="content-item-container">
        <img src="@/assets/images/category_wash.jpg" />
        <div class="text-content-item">Смесители</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.main-content-landing {
  display: flex;
  justify-content: space-between;
}

.content-item {
  width: 33%;
  padding: 16px;
}

.content-item-container {
  background: #fff;
}
.content-item img {
  background: grey;
  width: 100%;
  aspect-ratio: 1.2;
  object-fit: cover;
}
.content-item div {
  color: #000;
  text-align: center;
  padding: 0 0 5px 0px;
  font-weight: 600;
}
.text-content-item {
  padding-top: 5px;
}

@media (max-width: 965px) {
  .main-content-landing {
    flex-wrap: wrap;
  }

  .content-item {
    width: 50%;
  }
}
@media (max-width: 800px) {

  .content-item {
    width: 100%;
  }
}
</style>
