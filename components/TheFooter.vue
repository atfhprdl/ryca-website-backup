<template>
  <footer>
    <div class="container">
      <div class="row centerItem">
        <div class="col-lg-4">
          <div class="logos">
            <div class="logo"></div>
            <div class="logo"></div>
            <div class="logo"></div>
          </div>
        </div>
        <div class="col-lg-4">
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
        <div class="col-lg-4">
          <img class="header-logo" src="../assets/img/ryca-logo.png" alt="logo" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>

<style scoped>
footer{
  margin-top: 20px;
}
.logo {
  background-color: #9FC2FF;
  width: 35px;
  height: 35px;
  border-radius: 150px;
  margin-left: 20px;
}

.logos {
  justify-content: space-around;
  display: inline-flex;
}
.menu-container {
  display: inline-flex;
  justify-content:space-between;
  flex-direction: row;
  width: 100%;
}
img {
  float: left;
  width: 40%;
  height: auto;
}
</style>
