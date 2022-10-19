<template>
    <div>
        <section class="demo">
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
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: center;
    flex-direction: row;
}
</style>
