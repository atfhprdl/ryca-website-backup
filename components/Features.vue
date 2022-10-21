<template>
    <div>
         <div class="container">
                <div class="row centerItem">
                    <div class="col-lg-6">
                        <img class="jobs-vector" src="../assets/img/jobs-vector.svg" alt="jobs-vector">
                        </div>
                    <div class="col-lg-6">
                        <p class="font-medium ryca">
                            رایکا، فضایی برای یادگرفتن و اشتباه کردن است. ما همیشه از حضور افراد باانگیزه در تیم رایکا استقبال می کنیم.
                        </p>
                        <button class="font-regular btn"> فرصت های شغلی </button>
                        </div>
                </div>
        <div class="footer txt-container">
                <svg class="circle1" width="50" height="50" viewBox="0 0 50 50">
                    <path id="Subtraction_1" data-name="Subtraction 1" d="M45.2,66.2a24.979,24.979,0,0,1-25-25c0-.165,0-.333,0-.5H44.7V16.207c.2,0,.356,0,.5,0a25,25,0,1,1,0,50Z" transform="translate(-20.2 -16.202)" fill="rgb(69, 179, 242)"/>
                  </svg>
                <h4 class="font-bold doc">
                کارشناسان ما در تیم رایکا آماده پاسخگویی به سوالات شما می باشند
                </h4>
                <div class="font-medium row">
                    <div class="col-lg-4">
                        <div class="contact">
                            <img src="../assets/img/location.png">
                            <p class="location">شاهرود- پردیس رشد و فناوری های نوین دانشگاه صنعتی</p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="contact">
                            <img src="../assets/img/email.png">
                            <p class="email">support@ryca_team.com</p>
                        </div>
                    </div>
                    <div class="col-lg-4 boxs">
                        <div class="contact">
                            <img src="../assets/img/call.png">
                            <p >۰۲۳-۲۲۰۴۷۸۸۵ - ۰۹۱۱۹۴۴۲۵۳۹</p>
                        </div>
                    </div>
                </div>
            </div>
    </div>
    </div>
</template>

<script>
export default {
  name: 'CFeatures'
}
</script>

<style scoped>
.txt-container {
    position: relative;
}
.circle1 {
    width:40px;
    height: 40px;
    position: absolute;
    top: -20px;
    left: 85px;
    transform: rotate(180deg);
}
.contact {
    display: inline-flex;
    align-items: center;
}
.boxs {
    width: 80px;
    height: 80px;
    background-color: rgb(198, 234, 253);
}
.jobs-vector {
    margin:0px auto;
    width: 500px;
    height: 420px;
}
.doc {
    color: rgb(6, 19, 68);
    text-align: center;
    padding: 40px;
    margin-top: -75px;
    font-size: 20px;
    margin-bottom: auto;
}
.jobs-vector {
    margin:0px auto;
    width: 500px;
    height: 420px;
}
.ryca {
    font-size: 16px;
}
.footer {
    width: 100%;
    left: 0px;
    background-color: rgb(198, 234, 253);
}
img {
    margin: 20px;
    width: 30px;
    height: 30px;
}
</style>
