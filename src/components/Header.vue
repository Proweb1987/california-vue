<template>
  <div class="Header">
    <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
        <div class="header__content">
            <h1 class="header__content-title">The new phones are here take a look.</h1>
            <p class="header__content-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Scelerisque in est dui, aliquam, tempor. Faucibus morbi turpis.</p>
            <a href="#" class="header__content-btn">Explore</a>
        </div>
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner slide__img">
    <div class="carousel-item active">
      <img src="../assets/images/header-img1.png" class="slide__img" alt="...">
    </div>
    <div class="carousel-item">
      <img src="../assets/images/header-img2.png" class="slide__img" alt="...">
    </div>
    <div class="carousel-item">
      <img src="../assets/images/header-img3.jpg" class="slide__img" alt="...">
    </div>
  </div>
</div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped> 
  .slide__img {
    width: 650px;
    height: 550px;
  }
  .header__content-title {
    font-weight: 400;
    font-size: 58px;
    line-height: 70px;
    color: black;
    max-width: 588px;
    width: 100%;
  }
  .header__content-text {
    max-width: 565px;
    width: 100%;
    color: black;
    font-size: 16px;
    line-height: 19px;
  }
  .header__content-btn {
    font-size: 18px;
    line-height: 22px;
    color: black;
    text-transform: capitalize;
    border: 1px solid black;
    border-radius: 200px;
    width: 170px;
    padding: 12px 0;
    text-align: center;
    display: block; 
  }
  .slide {
    display: flex;
    align-items: center;
    background: #DCE5E2;
    border-radius: 32px;
    padding: 0 0 0 55px;
    margin-top: 30px;
  }
 



@media (max-width: 992px) {
    .slide {
        flex-direction: column;
        padding-top: 20px;
        padding-left: 0;
    }
    .header__content-title {
        text-align: center;
    }
    .header__content-text {
        text-align: center;
    }
    .header__content-btn {
        text-align: center;
        margin: 0 auto;
    }
    .slide__img {
        width: 100%;
        object-fit: cover;
    }
}
@media (max-width: 700px) {
    .header__content-title {
        font-size: 35px;
        line-height: 40px;
    }
}
</style>