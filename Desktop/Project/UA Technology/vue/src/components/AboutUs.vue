<template>
  <div class="container">
    <div class="about-write">
      <div class="about">
        <h3>01 | Biz Haqimizda</h3>
        <!-- <div class="hr">
          <h4></h4>
          <hr />
        </div> -->
      </div>
      <div class="clientHelp">
        <img  class="group" src="src/assets/images/Group 2.png" alt="" />
        <div class="UA-techno">
          <h4>
            UA TECHNOLOGIES innovatsion va zamonaviy dasturiy mahsulotlarni
            yaratish va raqamli texnologiyalar doirasida zarur bo‘lgan barcha
            zaruriy mahsulot operatsiyalari, loyihalash, ishlab chiqish,
            sinovdan o‘tkazish va uzluksiz yetkazib berish xizmatlarini taqdim
            etadi.
          </h4>
          <p>
            Mijozlarning ehtiyojlarini qondirish va mijozlarimizga uzluksiz
            sifatli mahsulotlarni taqdim etish bo'yicha harakatlarimiz va
            majburiyatimiz ularning ishonchini qozonishimizga yordam beradi.
          </p>
        </div>
        <div class="yellow-png">
          <img src="src/assets/images/yellow.png" alt="" />
        </div>
      </div>
    </div>

    <div class="About">
      <div class="MaskPage">
        <img class="MaskCard" src="src/assets/images/Mask.png" alt="" />
      </div>

      <div class="About-write">
        <div>
          <li>
            <img src="src/assets/images/True.png" alt="" />
            <p>Texnik mukammalik bizda doim birinchi o‘rinda turadi</p>
          </li>
          <li>
            <img src="src/assets/images/True.png" alt="" />
            <p>Har qanday loyiha uchun yechimlarni taklif qila olamiz</p>
          </li>
          <li>
            <img src="src/assets/images/True.png" alt="" />
            <p>Biznesingiz o’sish jarayoni biz bilan tezlashadi</p>
          </li>
        </div>

        <div class="Aziz-Hamidov">
          <div>
            <h4>Aziz Hamidov</h4>
            <h5>
              UA Technologies <br />
              ta’sischisi
            </h5>
          </div>

          <img src="src/assets/images/imzo.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>
<style  scoped>
.about {
  max-width: 1440px;
  margin: auto;
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 20px;
}

.about h3 {
  color: blue;
}
.about h4 {
  display: flex;
}
.hr {
  display: flex;
  gap: 40px;
  color: white;
}
hr {
  width: 700px;
  display: flex;
}

.clientHelp {
  display: flex;
  align-items: center;
}
.group {
  height: 130px;
}
.UA-techno p {
  font-size: 18px;
}
.MaskCard {
  width: 100%;
}

.About {
  display: flex;
  margin-top: 80px;
  align-items: center;
  text-align: center;
  width: 100%;
}
.About-write {
  display: flex;
  width: 90%;
  margin: auto;
  align-items: center;
}

.About-write img {
  width: 25px;
  height: 25px;
}
.About-write .Aziz-Hamidov {
  display: flex;
  text-align: center;
  justify-content: center;
  margin-top: 30px;
  display: flex;
  flex-wrap: wrap;
  width: 100%;
}
.Aziz-Hamidov img {
  margin-left: 40px;
  width: 300px;
  height: 80px;
}
li {
  display: flex;
  gap: 20px;
}
@media only screen and (max-width: 840px) {
.hr hr{
  width: 100%;
  max-width: 600px;
}
  .about {
    width: 100%;
    margin: auto;
    padding: 0;
  }
  .yellow-png img {
    display: none;
  }

  .MaskCard {
    width: 100%;
    display: block;
  }
  .Aziz-Hamidov {
    margin: 0;
    padding: 0;
  }
  .Aziz-Hamidov img {
    width: 100px;
  }
  .clientHelp {
    margin-top: 30px;
    width: 100%;
  }
  .About {
    display: block;
  }
  .About-write {
    margin: 50px;
    display: block;
  }
}
@media only screen and (max-width: 578px) {

  .UA-techno h4{
display: block;
font-size: 30px;
}
}
</style>













