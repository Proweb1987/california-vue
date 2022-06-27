<template>
  <div class="footer">
    <div class="footer__content">
        <img src="../assets/images/nav-logo.png" alt="" class="footer__content-img">
        <p class="footer__content-text">Sign up for texts to be notified about our best offers on the perfect gifts.</p>
    </div>
    <div class="footer__btns">
    <ul class="footer__list">
        <h5 class="footer__title">All Products</h5>
        <li class="footer__link">Phones</li>
        <li class="footer__link">Watch</li>
        <li class="footer__link">Tablet</li>
        <li class="footer__link">LapTop</li>
    </ul>
    <ul class="footer__list">
        <h5 class="footer__title">Company</h5>
        <li class="footer__link">About</li>
        <li class="footer__link">Support</li>
    </ul>
    <ul class="footer__list">
        <h5 class="footer__title">Support</h5>
        <li class="footer__link">Style Guid</li>
        <li class="footer__link">Licensig</li>
        <li class="footer__link">Change Log</li>
        <li class="footer__link">Contact</li>
    </ul>
    <ul class="footer__list">
        <h5 class="footer__title">Follow Us</h5>
        <li class="footer__link">Instagram</li>
        <li class="footer__link">Facebook</li>
        <li class="footer__link">Linkedin</li>
        <li class="footer__link">Youtube</li>
    </ul>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.footer {
    background: #F8F9FA;
    display: flex;
    justify-content: space-between;
    padding: 50px;
}
 .footer__content-text{
    font-size: 16px;
    line-height: 19px;
    color: black;
    width: 304px;
    margin-top: 18px;
 }
 .footer__title {
    font-weight: 400;
    font-size: 22px;
    line-height: 28px;
    color: black;
 }
 .footer__link {
    font-size: 17px;
    line-height: 22px;
    color: black;
    opacity: 0.7;
 }
 .footer__list {
    display: flex;
    flex-direction: column;
    row-gap: 15px;
 }
 .footer__btns {
    display: flex;
 }
 
 
 
 @media (max-width: 992px) {
  .footer {
    flex-direction: column;
  }
  .footer__content-text {
    text-align: center;
  }
  .footer__btns {
    display: flex;
    justify-content: center;
  }
  .footer__content {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
 }
 @media (max-width: 685px) {
    .footer__btns {
        flex-wrap: wrap;
        gap: 25px;
    }
    .footer__list {
        padding-left: 0;
        display: flex;
        align-items: center;
    }
 }
</style>