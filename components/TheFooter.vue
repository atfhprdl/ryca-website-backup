<template>
    <div>
        <section class="demo">
            <div class="social-icons-btn">
  <a class="icons facebook"  href="">
    <ion-icon name="logo-facebook"></ion-icon>
  </a>
  <a class="icons instagram"  href="">
    <ion-icon name="logo-instagram"></ion-icon>
  </a>
  <a class="icons linkedin"  href="">
    <ion-icon name="logo-linkedin"></ion-icon>
  </a>
                <div>
                    <span><i class="fa fa-twitter"></i></span>
                    <span><i class="fa fa-instagram"></i></span>
                    <span><i class="fa fa-whatsapp"></i></span>
                    <ul class="font-regular ftr">
                        <li> درباره ما </li>
                        <li> خدمات </li>
                        <li> دستاوردها </li>
                        <li> تماس با ما </li>
                    </ul>
                    <img class="ryca-logo" src="../assets/img/ryca-logo.png" alt="logo">
                </div>
            </div>
            </section>
    </div>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>

<style scoped>
.ftr {
    display: contents;
    list-style-type: none;
    font-size: 13px;
}
.ryca-logo {
    height:20px;
}
.demo div {
    width: 100%;
    height: 100px;
    justify-content: space-around;
}
* {
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.social-icons-btn {
  display: flex;
}
.icons {
  width: 20px;
  height: 20px;
  font-size: 2.5rem;
  font-weight: 500;
  text-decoration: none;
  background: rgb(161, 195, 252);
  margin: 0.2rem;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  box-shadow: 0 2px 2px #d1d1d1;
  color: #000;
  cursor: pointer;
  transition:
    all 0.15s ease;
}
.twitter:hover {
  background: #00ECEE;
}
.facebook:hover {
  background: #4267B2;
}
.instagram:hover {
  background-image:
    linear-gradient(#8a3ab9,#e95950, #bc2a8d, #fccc63);
}
.linkedin:hover {
  background: #0A66C2;
}
</style>
