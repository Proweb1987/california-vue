<template>
  <div class="best">
    <h4 class="best__title">See the best around here</h4>
    <p class="best__text">Our new Limited Edition Winter Design BESPOKE 4-Door Flex™</p>
    <div class="best__box">
        <div class="best__box-item">
            <p class="best__item-text">Smart light bulb pack</p>
            <h4 class="best__item-title">Latest and gratest</h4>
            <a href="#" class="best__item-btn">Explore</a>
            <img src="../assets/images/best-img1.png" alt="" class="best__item-img">
        </div>
        <div class="best__box-item">
            <p class="best__item-text">Smart light bulb pack</p>
            <h4 class="best__item-title">Best selling</h4>
            <a href="#" class="best__item-btn">Explore</a>
            <img src="../assets/images/best-img2.png" alt="" class="best__item-img">
        </div>
        <div class="best__box-item">
            <p class="best__item-text">Smart light bulb pack</p>
            <h4 class="best__item-title">Every product</h4>
            <a href="#" class="best__item-btn">Explore</a>
            <img src="../assets/images/best-img3.png" alt="" class="best__item-img">
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
 .best__title {
    font-weight: 400;
    font-size: 42px;
    line-height: 52px;
    color: black;
    text-align: center;
 }
 .best__text {
    font-size: 13px;
    line-height: 17px;
    color: black;
    text-align: center;
 }
 .best__item-text {
    font-size: 13px;
    line-height: 17px;
    color: black;
 }
 .best__item-title {
    font-size: 28px;
    line-height: 35px;
    color: black;
 }
 .best__item-btn {
    font-size: 18px;
    line-height: 22px;
    color: black;
    text-transform: capitalize;
    width: 190px;
    display: block;
    border: 1px solid #000000;
    border-radius: 200px;
    padding: 12px 0;
    text-align: center;
    margin: 30px 0;
 }
 .best__box-item {
    background: #F8F9FA;
    border-radius: 16px;
    max-width: 413px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 40px;
 }
 .best__box {
    display: flex;
    justify-content: space-between;
    gap: 30px;
    margin-top: 55px;
 }
 .best {
    margin-top: 75px;
 }
 
 
 
 @media (max-width: 1140px) {
    .best__box {
        flex-wrap: wrap;
        justify-content: center;
    }
 }
 @media (max-width: 576px) {
    .best__title {
        font-size: 35px;
        line-height: 40px;
    }
    .best__item-img {
        width: 100%;
    }
 }
</style>