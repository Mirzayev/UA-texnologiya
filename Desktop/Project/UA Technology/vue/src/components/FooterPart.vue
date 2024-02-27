<template>
  <div class="container">
    <div class="all-page">
      <div class="header">
        <h2>
          <span>
            Biznesingizni biz bilan kengaytiring <br />
            Biz xizmat ko‘rsatishdan doim mamnunmiz!
          </span>
        </h2>
        <button>Bog'lanish</button>
      </div>
      <div class="footer">
        <div class="logotip">
          <img src="src/assets/images/Group.png" alt="" />
          <div class="link">
            <img src="src/assets/images/instagram-icon.png" alt="" />
            <img src="src/assets/images/telegram-icon.png" alt="" />
            <img src="src/assets/images/twitter-icon.png" alt="" />
          </div>
        </div>
        <div class="">
          <h5>Biz Haqimizda</h5>
          <p>
            Innovatsion va zamonaviy dasturiy mahsulotlarni yaratish va raqamli
            texnologiyalar doirasida zarur bo‘lgan barcha zaruriy mahsulot
            operatsiyalari, loyihalash, ishlab chiqish, sinovdan o‘tkazish va
            uzluksiz yetkazib berish xizmatlarini taqdim etamiz.
          </p>
          <div class="clock-icon">
            <img src="src/assets/images/clock-icon.png" alt="" />
            <div>
              <h6>Ish soatlari</h6>
              <h6>Dushanba-Juma 9:00-17:00</h6>
            </div>
          </div>
          <div class="earphone-icon">
            <img src="src/assets/images/earphone-icon.png" alt="" />
            <h6>Biz Bilan Bog’lanish</h6>
            <h6>24/7 365</h6>
          </div>
        </div>
        <div class="connection">
          <h5>Bog’lanish</h5>
          <div class="email-icon">
            <img src="src/assets/images/email-icon.png" alt="" />
            <h6>info@autechnologies.com</h6>
          </div>
          <div class="phone-icon">
            <img src="src/assets/images/carbon-phone.png" alt="" />
            <h6>998-99-9990099</h6>
            <div></div>
          </div>
        </div>
        <div class="footer-sevice">
          <h5>Bizning Xizmatlar</h5>
          <h6>Veb-sayt</h6>
          <h6>Logo va Brending</h6>
          <h6>CRM tizimlar</h6>
          <h6>UI&UX dizayn</h6>
          <h6>Mobil ilovalar</h6>
          <h6>Veb-sayt</h6>
        </div>
      </div>
    </div>
  </div>
</template>
  


  <script setup>
</script>
  



  <style  scoped>
.all-page {
  width: 100%;
  position: relative;
  background: rgba(19, 14, 41, 1);
  margin-top: 300px;
  padding-top: 100px;
}
.header {
  position: absolute;
  top: -50%;
  left: 23%;
  max-width: 1440px;
  margin-top: 150px;
  background: linear-gradient(261.54deg, #a69f29 -183.02%, #25166f 78.94%);
  text-align: center;
  padding: 30px 50px;
  border-radius: 20px;
}
.header {
  color: white;
}
.header button {
  padding: 4px 10px;
  border-radius: 20px;
  background: yellow;
  border: none;
}
.header button:hover {
  color: rgb(78, 71, 71);
  background: rgb(200, 200, 90);
}
.logotip {
  text-align: center;
}
.link {
  margin-top: 20px;
  display: flex;
  gap: 10px;
  text-align: center;
  justify-content: center;
}
.link img:hover {
  cursor: pointer;
  transform: scale(1.2);
}
.footer {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  flex-wrap: wrap;
  margin: 60px auto;
  background: rgba(19, 14, 41, 1);
  width: 90%;
  gap: 20px;
}
@media only screen and (max-width: 1080px) {
  .footer {
    display: grid;
    grid-template-columns: repeat(3, 1.2fr);
  }
}

@media only screen and (max-width: 768px) {
  .header{
   position: absolute;
   top: -40%;
   left: 5%;
  }

  .footer {
    display: flex;
    text-align: left;

  }
  .logotip {
    align-items: center;
    gap: 40px;
    margin: 0;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
  }
  .link {
    margin: 0;
  }
}

.clock-icon {
  display: flex;
  align-items: center;
  gap: 10px;
  margin: 0;
  padding: 0;
}
.clock-icon img {
  width: 20px;
  height: 20px;
}
.earphone-icon {
  display: flex;
  margin-top: 15px;
  gap: 10px;
}
.email-icon {
  display: flex;
  margin-top: 20px;
  gap: 10px;
}
.phone-icon {
  display: flex;
  margin-top: 30px;
  gap: 10px;
}
h5 {
  color: white;
}
</style>