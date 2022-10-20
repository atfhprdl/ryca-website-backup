<template>
<div>
    <img src="../assets/img/hero-background.png" alt="background image" class="hero-background-image">
    <div class="container">
            <div class="row centerItem">
                <div class="col-lg-8">
                    <ul class="font-regular menu">
                        <li> درباره ما </li>
                        <li> خدمات </li>
                        <li> دستاوردها </li>
                        <li> تماس با ما </li>
                    </ul>
                </div>
             <div class="col-lg-4">
                <img src="../assets/img/ryca-logo.png" alt="logo">
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
.menu li {
    display: inline-block;
    list-style-type: none;
    margin: 20px 10px;
    font-size: 16px;
}
</style>
