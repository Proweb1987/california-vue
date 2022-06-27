<template>
  <div class="Navbar">
    <nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="#">
        <img src="../assets/images/nav-logo.png" alt="" class="nav__logo">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" fill="currentColor" class="bi bi-three-dots" viewBox="0 0 16 16">
  <path d="M3 9.5a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zm5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zm5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3z"/>
</svg>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link nav__btn" aria-current="page" href="#">all products</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle nav__btn" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Solutions
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Iphone</a></li>
            <li><a class="dropdown-item" href="#">Macbook</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Imac</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link nav__btn" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link nav__btn" href="#" tabindex="-1" aria-disabled="true">Support</a>
        </li>
      </ul>
      <form class="icons d-flex">
        <img src="../assets/images/nav-cart.png" alt="" class="nav__cart">
        <img src="../assets/images/nav-search.png" alt="" class="nav__search">
      </form>
    </div>
  </div>
</nav>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
 .icons {
    gap: 10px;
 }
 .nav__btn {
    font-size: 14px;
    line-height: 17px;
    color: black;
    text-transform: uppercase;
 }
 .Navbar {
    padding: 30px 0;
 }
 .dropdown-menu {
    width: max-content;
 }
 .navbar-nav {
    display: flex;
    justify-content: center;
    width: 100%;
    gap: 15px;
 }
</style>