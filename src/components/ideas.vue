<template>
  <div class="ideas">
    <h4 class="ideas__title">Ideas have a place here</h4>
    <p class="ideas__text">Our new Limited Edition Winter Design BESPOKE 4-Door Flex™</p>
    <div class="ideas__content">
        <img src="../assets/images/ideas-img.png" alt="" class="ideas__content-img">
        <div class="ideas__content-info">
           <p class="ideas__content-text">We Make It Easy To Find The Great Design Talent, Easier...</p> 
           <p class="ideas__content-text">Road Design Handbook For The International Road...</p> 
           <p class="ideas__content-text">The Best Kept Secrets About Creative People</p> 
           <p class="ideas__content-text">We Make It Easy To Find The Great Design Talent, Easier...</p> 
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.ideas {
    margin-top: 50px;
}
.ideas__content {
    display: flex;
    justify-content: space-between;
    gap: 28px;
    margin-top: 40px;
}
.ideas__content-info {
    margin-top: 28px;
}
.ideas__title {
    font-weight: 400;
    font-size: 42px;
    line-height: 52px;
    color: black;
    text-align: center;
}
.ideas__text {
    font-size: 13px;
    line-height: 17px;
    color: black;
    text-align: center;
}
.ideas__content-text {
    font-size: 24px;
    line-height: 30px;
    color: black;
    max-width: 569px;
    width: 100%;
}


@media (max-width: 992px) {
    .ideas__content {
        flex-wrap: wrap;
        justify-content: center;
    }
    .ideas__content-text {
     text-align: center;
    }
    .ideas__content-img {
        width: 100%;
    }
}
@media (max-width: 576px) {
 .ideas__title {
    font-size: 35px;
    line-height: 40px;
 }
}
</style>