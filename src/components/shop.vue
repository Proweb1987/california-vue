<template>
  <div class="shop">
    <h2 class="shop__title">Shop our latest offers and categories</h2>
    <p class="shop__text">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Scelerisque in
      est dui, aliquam, tempor. Faucibus morbi turpis. Lorem ipsum dolor sit
      amet, consectetur adipiscing elit.
    </p>
    <div class="shop__box">
      <div class="shop__leftSide">
        <div class="shop__box-item">
          <img
            src="../assets/images/shop-img1.png"
            alt=""
            class="shop__item-img"
          />
          <div class="shop__item-info">
            <p class="shop__item-text">Laptops</p>
            <h2 class="shop__item-title">True Laptop Solution</h2>
          </div>
        </div>
        <div class="shop__box-item shop__two">
          <img
            src="../assets/images/shop-img3.png"
            alt=""
            class="shop__item-img watch"
          />
          <div class="shop__item-info">
            <p class="shop__item-text">Watch</p>
            <h2 class="shop__item-title">Not just stylisht</h2>
          </div>
        </div>
      </div>
      <div class="shop__rightSide">
        <div class="shop__box-item rightSide__item">
            <img src="../assets/images/shop-img2.png" alt="" class="shop__item-img">
            <p class="shop__item-text rightSide__text">Phones</p>
            <h2 class="shop__item-title rightSide__title">Your day to day life</h2>
        </div>
        <div class="shop__box-item rightSide__item">
            <p class="shop__item-text rightSide__text">Tablet</p>
            <h2 class="shop__item-title rightSide__title title">Empower your work</h2>
            <img src="../assets/images/shop__img4.png" alt="" class="shop__item-img">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.shop__title {
  font-weight: 400;
  font-size: 42px;
  line-height: 52px;
  max-width: 780px;
  width: 100%;
  color: black;
  text-align: center;
  margin: 0 auto;
  margin-top: 75px;
}
.shop__text {
  max-width: 628px;
  width: 100%;
  text-align: center;
  font-size: 14px;
  line-height: 17px;
  color: black;
  margin: 20px auto;
}
.shop__item-text {
  font-size: 15px;
  line-height: 19px;
  color: black;
}
.shop__box-item {
  background: #ffffff;
  border-radius: 32px;
  padding: 0 42px;
  max-width: 639px;
  width: 100%;
}

.shop__item-title {
  font-weight: 400;
  font-size: 32px;
  line-height: 38px;
  color: black;
  width: 192px;
  text-align: right;
}
.shop__item-info {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}
.shop__two {
  display: flex;
  align-items: center;
  margin-top: 72px;
}
.shop__item-info {
  margin-left: 30px;
  overflow: hidden;
}
.rightSide__item {
    max-width: 312px;
    width: 100%;
    padding: 144px 0 281px 16px;
    height: 792px;
}
.shop__item-img {
    width: 100%;
}
.rightSide__text {
    text-align: center;
    margin-top: 20px;
    margin-bottom: 40px;
    padding-right: 16px;
}
.rightSide__title {
    text-align: center;
    margin: 0 auto;
    padding-right: 16px;
}
.title {
    margin-bottom: 40px;
}
.shop__box {
    display: flex;
    width: 100%;
    gap: 16px;
}
.shop__rightSide {
    display: flex;
    width: 100%;
    gap: 16px;
}
.watch {
    width: max-content;
}




@media (max-width: 1100px) {
    .shop__box {
        flex-wrap: wrap;
        justify-content: center;
    }
    .shop__rightSide {
        justify-content: center;
    }
}
@media (max-width: 768px) {
    .shop__leftSide {
        width: 100%;
    }
    .shop__rightSide {
        width: 100%;
    }
    .shop__box-item {
        margin: 30px auto;
    }
    .shop__two {
        flex-direction: column;
    }
    .shop__item-text {
        text-align: center;
        width: 100%;
        margin-top: 20px;
    }
    .shop__item-title {
        text-align: center;
    }
    .shop__item-info {
        margin-left: 0;
    }
}
@media (max-width: 576px) {
  .shop__item-img {
    width: 100%;
  }
  .shop__rightSide {
    flex-direction: column;
  }
}
</style>