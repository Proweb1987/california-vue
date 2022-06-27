<template>
  <div class="product">
    <h3 class="product__title">Save on our most selled items.</h3>
    <p class="product__text">Our new Limited Edition Winter Design BESPOKE 4-Door Flex™</p>
    <div class="product__box">
      <div class="product__box-item">
        <img src="../assets/images/product-img1.png" alt="" class="product__item-img">
        <h3 class="product__item-title">MacBook Pro 13</h3>
        <p class="product__item-text">Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit...`</p>
        <p class="product__item-price">$ 1,200.00 USD</p>
      </div>
      <div class="product__box-item">
        <img src="../assets/images/product-img2.png" alt="" class="product__item-img">
        <h3 class="product__item-title">Smart Galaxy Watch 3</h3>
        <p class="product__item-text">Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit...</p>
        <p class="product__item-price">$ 199.00 USD</p>
      </div>
      <div class="product__box-item">
        <img src="../assets/images/product-img3.png" alt="" class="product__item-img">
        <h3 class="product__item-title">MacBook Air M1</h3>
        <p class="product__item-text">Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit...</p>
        <p class="product__item-price">$ 1,009.00 USD</p>
      </div>
      <div class="product__box-item">
        <img src="../assets/images/product-img4.png" alt="" class="product__item-img">
        <h3 class="product__item-title">iPad</h3>
        <p class="product__item-text">Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit...</p>
        <p class="product__item-price">$ 610.00 USD</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.product__title {
  font-weight: 400;
  font-size: 42px;
  line-height: 52px;
  text-align: center;
  color: black;
}
.product__text {
  font-size: 13px;
  line-height: 17px;
  color: black;
  text-align: center;
}
.product__item-title {
  font-weight: 400;
  font-size: 22px;
  line-height: 28px;
  color: black;
  margin-top: 10px;
}
.product__item-text {
  font-size: 14px;
  line-height: 17px;
  width: 261px;
  color: #4B4B4B;
}
.product__item-price {
  font-size: 18px;
  line-height: 22px; 
  color: black; 
}
.product__box {
 display: flex;
 justify-content: space-between;
 margin-top: 60px;
 flex-wrap: wrap;
}
.product {
  margin-top: 80px;
}



@media (max-width: 1075px) {
  .product__box {
    justify-content: center;
    gap: 50px;
  }
}
@media (max-width: 576px) {
  .product__title {
    font-size: 35px;
    line-height: 40px;
  }
}
</style>