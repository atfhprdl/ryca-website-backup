<template>
<div>
    <div class="container">
        <div class="row centerItem">
        <div class="col-lg-6">
            <!-- <div style="width:80%"> -->
                <h1 class="font-black">
                    جایی که <span style="color: rgb(91, 157, 252);">نــوآوری</span><br> با دنیای واقعی روبرو می شود
            </h1>
            <p class="font-medium">
                ما راه حل های دیجیتالی ارائه می کنیم که استفاده و مدیریت آن ها آسان است و به راحتی قابل اعتماد هستند.
            </p>
            <button class="font-regular btn"> درباره ما </button>
            <img class="wifi-icon" src="../assets/img/wifi-icon.svg" alt="wifi">
            <img class="monitor-icon" src="../assets/img/monitor-icon.svg" alt="monitor">
         </div>
        <div class="col-lg-6">
            <img class="hero-vector" src="../assets/img/hero-vector.svg" alt="hero-vector">
        </div>
    </div>
    </div>
                <div class="contianer txt-container">
                <svg class="circle" width="50" height="50" viewBox="0 0 50 50">
                    <path id="Subtraction_1" data-name="Subtraction 1" d="M45.2,66.2a24.979,24.979,0,0,1-25-25c0-.165,0-.333,0-.5H44.7V16.207c.2,0,.356,0,.5,0a25,25,0,1,1,0,50Z" transform="translate(-20.2 -16.202)" fill="rgb(69, 179, 242)"/>
                  </svg>
                <div class="txt">
                    <p class="font-medium">
                        <span>آوای هوشمند رایکا</span>،
         حاصل تفکر تیمی خلاق بوده که از سال ۱۳۹۸ فعالیت خود را در زمینه تامین و تولید نیازهای سیستمی و نرم افزاری
          شروع کرده است.نقطه اتکای رایکا، تیم باانگیزه و جوانیست که شوق پیشرفت و یادگیری را زنده نگه می دارند.
                    </p>
                </div>
            </div>
</div>
</template>

<script>
export default {
  name: 'TheHeader'
}
</script>

<style scoped>
.wifi-icon {
    position: absolute;
    width: 40px;
    height: auto;
    top: -40%;
    right: 83%;
}

.monitor-icon {
    position: absolute;
    width: 45px;
    height: auto;
    top: 110%;
    right: 60%;
}
.hero-vector {
    margin:0px auto;
    width: 450px;
    height: 500px;
}
h1 {
    color: rgb(6, 19, 68);
    font-size: 30px;
}
.txt-container img {
    position: absolute;
    width: 30px;
    height: 30px;
    margin: 20px;
}

.txt {
    display: block;
    width: 90%;
    margin-right: auto;
    margin-left: auto;
    padding: 20px;
    height: 100px;
    background-color: rgb(198, 234, 253);
    box-sizing: border-box;
    border-radius: 20px;

}

.circle{
    width:40px;
    height: 40px;
    position: absolute;
    top: -20px;
    right: 48%;
    transform: rotate(180deg);
}

.txt p {
    text-align: center;
}

.txt p span {
    color: rgb(69, 179, 242);
}
</style>
