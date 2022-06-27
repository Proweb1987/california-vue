<template>
  <div class="wrapper">
    <div class="container">
      <Nav/>
      <Header/>
      <Shop/>
      <Product/>
      <Best/>
      <Ideas/>
      <Search/>
      <Email/>
      <Footer/>
    </div>
  </div>
</template>

<script>
import Nav from '@/components/Nav.vue'
import Header from '@/components/Header.vue'
import Shop from '@/components/shop.vue'
import Product from '@/components/product.vue'
import Best from '@/components/best.vue'
import Ideas from '@/components/ideas.vue'
import Search from '@/components/search.vue'
import Email from '@/components/email.vue'
import Footer from '@/components/footer.vue'

export default {
 components: {
  Nav,
  Header,
  Shop,
  Product,
  Best,
  Ideas,
  Search,
  Email,
  Footer
 }
}
</script>

<style>
 
</style>
