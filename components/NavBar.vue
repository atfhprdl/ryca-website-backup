<template>
  <div>
    <img
      src="../assets/img/hero-background.png"
      alt="background image"
      class="hero-background-image"
    />
    <div class="container">
      <div class="row centerItem">
        <div class="col-lg-9">
          <div class="menu-container">
            <a href="#">
              <p class="font-regular">درباره ما</p>
            </a>
            <a href="#">
              <p class="font-regular">خدمات</p>
            </a>
            <a href="#">
              <p class="font-regular">دستاوردها</p>
            </a>
            <a href="#">
              <p class="font-regular">تماس با ما</p>
            </a>
          </div>
        </div>
        <div class="col-lg-3">
          <img src="../assets/img/ryca-logo.png" alt="logo" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style>
.hero-background-image {
    position: absolute;
    right: 0;
    top: 0;
    width: 100%;
    height: auto;
}

.menu-container {
    display: inline-flex;
    justify-content: space-between;
    flex-direction: row;
    width: 40%;
}

.menu-container a {
    text-decoration: none;
    color: black;
}

.header-logo {
    width: 50%;
    height: auto;
}
</style>
