<template>
  <div class="search">
    <h5 class="search__title">Looking for anything else?</h5>
    <div class="searching">
    <input 
    type="text" 
    class="search__input" 
    placeholder="Search keyword"
    >
    </div>
   <div class="search__buttons">
    <div class="btns">
    <button v-for="btn in array" class="search__button">{{ btn }}</button>
    </div>
    <div class="btns">
    <button v-for="item in arr" class="search__button">{{ item }}</button>
    </div>
   </div>
  </div>
</template>

<script>
export default {
 data() {
    return {
        array: ['iPhone','Charger','Gift','Google Pixel 3','Keyboard'],
        arr: ['13 Pro Max','iPhone 12','Laptop','Mobile']
    }
 }
}
</script>

<style scoped>
.search {
    position: relative;
    margin-top: 150px;
}
.search__title {
    font-weight: 400;
    font-size: 42px;
    line-height: 52px;
    color: black;
    text-align: center;
}
.search__buttons {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
}
.btns {
    display: flex;
    gap: 10px;
}
 .search__button {
    outline: none;
    border: none;
    padding: 12px 20px;
    background: #FFFFFF;
    border: 1px solid #C5C5C5;
    border-radius: 200px;
 }
 .search__input {
    background: #F8F9FA;
    border: 1px solid #C5C5C5;
    border-radius: 100px;
    max-width: 650px;
    width: 100%;
    padding: 22px 0 22px 65px;
    outline: none;
    margin-top: 24px;
    margin-bottom: 20px;
 }

 .searching {
    display: flex;
    justify-content: center;
 }



@media (max-width: 620px) {
    .btns {
        flex-wrap: wrap;
        justify-content: center;
    }
    .search__title {
        font-size: 35px;
        line-height: 40px;
    }
}
</style>