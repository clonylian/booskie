<template>
  <div class="about">
    <div class="head">
      <img src="../assets/2.png">
      <div class="head_one">
        <p><a href="https://booski.vercel.app/#/">Home</a></p>
        <p><a href="#one"> Partners</a></p>
        <p> <a href="#two">About</a></p>
        <p> <a href="#three">Tokenomics</a></p>
        <p> <a href="#four">Roadmap</a></p>
        <p> <a href="https://github.com/cyberscope-io/audits/blob/main/booskie/audit.pdf">Audit</a></p>
        <p> <a href="https://github.com/SecureBe/Audit-KYC/blob/main/Booskie%20KYC.pdf">KYC</a></p>
        <p><a href="#five">FAQs</a></p>
        <p><a @click="to" href="">Stake</a></p>
        <p><a href="#seve">Contact</a></p>
        <p @click="add">Connect</p>
      </div>
    </div>  
    <div class="cen_1">
      <img class="cen_img" src="../assets/1.png">
      <div class="cen_2">
        <a href="https://twitter.com/BooskieToken"><img src="../assets/tb_1.png"></a>
        <a href="https://t.me/booskie"><img src="../assets/tb_2.png"></a>
        <a href="https://www.facebook.com/profile.php?id=100094243596985"><img src="../assets/tb_3.png"></a>
        <a href="https://discord.gg/w4p4WqJFsE"><img src="../assets/tb_4.png"></a>
        <a href="#"><img src="../assets/tb_5.png"></a>
        <a href="#"><img src="../assets/tb_6.png"></a>
        <a href="#"><img src="../assets/tb_7.png"></a>
      </div>
      <div class="cen_3">
        <div class="com">
          Comming Soon
        </div>
      </div>
    </div>
    <div class="wave-about"></div>
    <div class="but">
      <div class="button" id="seve">
        <h1>EXPLORE
          <br>
          BooSkie
        </h1>
        <p>$BOOSKIE is a meme coin with no intrinsic value or expectation of financial return. It is simply a meme coin
          to HODL (Hold on for Dear Love). There is no formal team or utilities. The coin is completely useless and for
          entertainment purposes only. But things can change in the future?</p>
        <div class="but_2">
          <a href="https://twitter.com/BooskieToken"><img src="../assets/tb_1.png"></a>
          <a href="https://t.me/booskie"><img src="../assets/tb_2.png"></a>
          <a href="https://www.facebook.com/profile.php?id=100094243596985"><img src="../assets/tb_3.png"></a>
          <a href="https://discord.gg/w4p4WqJFsE"><img src="../assets/tb_4.png"></a>
          <a href="#"><img src="../assets/tb_5.png"></a>
          <a href="#"><img src="../assets/tb_6.png"></a>
          <a href="#"><img src="../assets/tb_7.png"></a>
        </div>
        <div class="but_one">
          <a href="https://github.com/SecureBe/Audit-KYC/blob/main/Booskie%20KYC.pdf">
            <img class="but_o1" src="../assets/15.png">
          </a>
          <a href="https://github.com/cyberscope-io/audits/blob/main/booskie/audit.pdf">
            <img class="but_o2" src="../assets/12.png">
          </a>
        </div>
        <div class="but_two">
          info@booskie.com
          <br>
          BooSkie 2023 - All Rights Reserved
        </div>
      </div>
    </div>
  </div>
</template>
<script>
</script>
<style>
.about {
  width: 100%;
  /* padding-bottom: 12rem; */
  background-image: url('../assets/17.jpg');
}

.head {
  width: 100%;
  /* // height: 8rem; */
  background-color: rgba(245, 139, 159, 0.6);
  display: flex;
  justify-content: space-between;
  align-items: center;


}

.head>img {
  width: 80px;
  height: 80px;
  margin-left: 2.5rem;
}

.head_one {
  display: flex;
  color: white;
  width: 48rem;
  margin-right: 3rem;
  justify-content: space-between;
  font-family: four;
  font-size: 16px;
  margin-right: 5rem;
  height: 8rem;
  align-items: center
}

.head_one>p>a {

  color: white;
}

.cen_1 {
  width: 60%;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
  padding-bottom: 10rem;
}

.cen_img {
  margin-top: 3rem;
  width: 580px;
  height: 580px;
}

.cen_2 {
  /* // width: 80%; */
  display: flex;
  margin: 2rem 0 1rem 0;
}

.cen_2>a {
  margin-left: 1rem;
}

.cen_2>a>img {
  width: 60px;
  height: 60px;
}

.cen_3 {
  width: 60%;
  background-color: rgb(235, 42, 100);
  text-align: center;
  padding: 1rem;
  border-style: dashed;
  border-width: 2px;
  border-style: dashed;
  border-color: white;
  color: white;
  margin-bottom: 5rem
}

.com {
  font-size: 30px;
  color: white;
}

.but {
  width: 100%;
  background-color: white;
  padding-top: 10rem;
}

.button {
  width: 60%;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}

.button h1 {
  text-align: center;
  color: rgb(234, 41, 99);
  font-family: three;
  font-size: 60px;
  line-height: 55px;
}

.button>p {
  max-width: 860px;
  width: 82%;
  margin: 1rem 0 1rem 0;
  font-size: 14px;
  color: rgb(242, 131, 150);
  text-align: center;
}

.but_2 {
  /* // width: 80%; */
  display: flex;
  margin: 2rem 0 1rem 0;
}

.but_2>a {
  margin-left: 1rem;
}

.but_2>a>img {
  width: 40px;
  height: 40px;
}

.but_one {
  display: flex;
  align-items: center;
}

.but_o1 {
  width: 240px;
  height: 153px;
}

.but_o2 {
  width: 285px;
  height: 85px;
}

.but_two {
  color: rgb(242, 131, 150);
  text-align: center;
  font-family: four;
}
.wave-about{
  width: 100%;
  height: 20rem;
  background-image: url('../assets/img1.png');
  background-size: 100% 100%;
  background-repeat: no-repeat;
  position: absolute;
  top: 120%;
}

@media (max-width: 600px) {
  .head_one {
    display: none;
  }

  .head {
    justify-content: center;
  }

  .cen_img {
    width: 350px;
    height: 350px;
  }

  .cen_1 {
    width: 100%;
  }

  .cen_2 {
    width: 95%;
    flex-wrap: wrap;
    justify-content: center;
  }

  .cen_2>a>img {
    width: 50px;
    height: 50px;
  }

  .cen_3 {
    width: 85%;
    font-size: 12px;
  }

  .cen_4 {
    width: 99%;
  }

  .cen_4>h1 {
    font-size: 60px;
  }

  .cen_5 {
    justify-content: space-around;
    flex-direction: column;
  }

  .cen_5>div {
    width: 98%;
  }

  .cen_6 {
    justify-content: space-around;
    flex-direction: column;
  }

  .cen_6>div {
    width: 98%;
    align-items: center;
    justify-content: center;
  }

  .cen_tp6 {
    margin-bottom: 2rem;
  }

  .wave-div {
    width: 100%;
    height: 12rem;
    background-image: url("http://localhost:8080/img/img1.70baa066.png");
    background-size: 100% 100%;
    background-repeat: no-repeat;
    position: relative;
    top: -5%;
  }

  .xmd_one {
    width: 100%;
    flex-direction: column;
  }

  .xmd_two>img:nth-child(1) {
    width: 350px;
    height: 350px;
  }

  .head>img {
    margin-left: 0;
  }

  .xmo {
    height: 120rem;
  }

  .xmd_two {
    width: 100%;
  }

  .xmd_thre {
    width: 100%;
  }

  .xmd_thre>img {
    width: 290px;
    height: 79px;
  }

  .wave-divs {
    width: 100%;
    height: 12rem;
    background-image: url(http://localhost:8080/img/img1.70baa066.png);
    background-size: 100% 100%;
    background-repeat: no-repeat;
    position: relative;
    top: 10%;
  }

  .pink_one {
    width: 100%;
  }

  .pink_two>p {
    width: 90%;
    font-size: 12px;
  }

  .pink_four {
    width: 90%;
    flex-direction: column;
    align-items: center;
  }

  .pink_four>div {
    margin-bottom: 2rem;
  }

  .pink_ones {
    width: 90%;
  }

  .pink_ones>h1 {
    font-size: 55px;
  }

  .pink_four_1 {
    width: 21rem;
  }

  .pink_four_2 {
    width: 21rem;
  }

  .pink_four_3 {
    width: 21rem;
  }

  .wave-divsx {
    height: 12rem;
    top: -9%;
  }

  .road_ones {
    width: 85%;
    flex-direction: column;
  }

  .road_ones>div {
    margin-bottom: 2rem;
  }

  .road_two {
    width: 100%;
  }

  .road_three {
    width: 100%;
  }

  .road_four {
    width: 100%;
  }

  .wave-divsd {
    height: 12rem;
    top: 57%;
  }

  .xm_ann {
    flex-direction: column;
    align-items: center;
  }

  .xm_aone {
    width: 100%;
    margin-bottom: 2rem;
  }

  .xm_three {
    width: 100%;
  }

  .xm_three>img {
    width: 350px;
    height: 350px;
  }

  .wave-divsds {
    width: 100%;
    height: 13rem;
    background-image: url(http://localhost:8080/img/img1.70baa066.png);
    background-size: 100% 100%;
    background-repeat: no-repeat;
    position: absolute;
    top: 96%;
  }
  .wave-about{
    height: 12rem;
    top: 127%;
  }
  .clong {
    width: 80%;
  }

  .wave-divsdsb {
    width: 100%;
    height: 12rem;
    background-image: url(http://localhost:8080/img/img1.70baa066.png);
    background-size: 100% 100%;
    background-repeat: no-repeat;
    position: relative;
    top: 3%;
  }

  .button {
    width: 85%;
  }

  .but_2 {
    width: 80%;
    flex-wrap: wrap;
    justify-content: center;
  }

  .but_o1 {
    width: 80px;
    height: 55px;
  }

  .but_o2 {
    width: 102px;
    height: 35px;
  }

  .wave-divsboxd {
    height: 12rem;
  }
}
</style>