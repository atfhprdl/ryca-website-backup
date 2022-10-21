<template>
    <div>
        <div class="txt2">
                <h3 class="font-black">
                تجربیات دیجیتالی ایجاد می کنیم که <span> هیجان انگیز </span> و <span> الهام بخش</span> است
                </h3>
                <p class="font-medium">
                از جمله نتایج فعالیت چندساله رایکا طراحی و توسعه سامانه اتوماسیون حمل و نقل بار، سامانه جامع سهام و بایگانی می باشد.
                </p>
            </div>
            <section class='FlexContainer'>
            <div class="box-txt">
                <img class="logo" src="../assets/img/varef-logo.png">
            <p class="font-black">
            وارف، سامانه جامع سهام</p>
                <p class="font-regular">در این نرم افزار شرکت ها می توانند از طریق پنل شرکتی، اطلاعات اعضای شرکت را ثبت نمایند و مزان سهم و یا سهام فرد را مشخص کنند</p>
                <p class="font-medium"><a href="#"> بیشتر بخوانید </a></p>
                </div>
                <div class="box-txt">
            <img class="logo centerite" src="../assets/img/carvann-logo.png">
            <p class="font-black">
                کاروان، اتوماسیون حمل و نقل بار</p>
            <p class="font-regular">
            سامانه کاروان به آدرس carvann.ir در سه سال گذشته توانسته است اتوماسیون اعلام بار و نوبت دهی رانندگان ماشین های سنگین را راه اندازی کند</p>
                <p class="font-medium"><a href="#"> بیشتر بخوانید </a></p>
        </div>
        </section>
    </div>
</template>

<script>
export default {
  name: 'TheTeasers'
}
</script>

<style scoped>
h3 span {
    color: rgb(226, 69, 67);
}
h3 {
    color: rgb(6, 19, 68);
    text-align: center;
    margin-top: 100px;
}
.txt2 p {
    text-align: center;
}
.logo {
    padding: 70px 180px 20px 180px;
    width: 50px;
    height: 50px;
    text-align: center;
}
.FlexContainer {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: baseline;
    align-content: center;
    flex-direction: row;
    margin-top: 60px;
}
.FlexContainer div {
    width: 410px;
    height: 410px;
    margin: 10px;
    border-radius: 15px;
    background-color: #fff;
}
.box-txt {
    text-align: center;
    padding: 20px 15px;
}

.box-txt img {
    background-color: rgb(66, 141, 252);
    padding: 15px;
    border-radius: 100px;
    width: 30px;
    height: auto;
}
p a {
    text-decoration: none;
    color: rgb(69, 179, 242);
    text-align: center;
    margin-top: 10px;
}
</style>
