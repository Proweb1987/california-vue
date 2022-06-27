<template>
  <div class="email">
    <h5 class="email__title">Never miss a thing</h5>
    <p class="email__text">Sign up for texts to be notified about our best offers on the perfect gifts.</p>
    <img src="../assets/images/email-img.png" alt="" class="email__img">
    <div class="email__login">
    <input class="email__input" placeholder="Your email" type="text">
    <button class="email__button">Sign up</button>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.email {
    background: #DCE5E2;
    border-radius: 16px;
    padding: 47px 0 43px 0;
    max-width: 935px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 70px auto;
}
 .email__title {
    font-weight: 400;
    font-size: 42px;
    line-height: 52px;
    color: black;
    text-align: center;
 }
 .email__text {
    font-size: 16px;
    line-height: 19px;
    color: black;
    text-align: center;
 }
 .email__img {
    display: flex;
    justify-content: center;
    margin: 14px auto;
 }
 .email__login {
    display: flex;
    justify-content: center;
 }
 .email__input {
    padding: 16px 0 16px 30px;
    background: #DCE5E2;
    border: 1px solid #000000;
    border-radius: 54px 0px 0px 54px;
    outline: none;
    max-width: 285px;
    width: 100%;
 }
 .email__button {
    padding: 16px;
    background: #000000;
    border-radius: 0px 200px 200px 0px;
    color: white;
    max-width: 115px;
    width: 100%;
 }
 
 
 
 @media (max-width: 576px) {
    .email__title {
        font-size: 35px;
        line-height: 40px;
    }
 }
</style>