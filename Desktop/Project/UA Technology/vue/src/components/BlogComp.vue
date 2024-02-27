<template>
  <div>
    <div class="container">
      <div class="header">
        <div class="header-start">
          <h5>
            03 |
            <h6>Blog</h6>
          </h5>
        </div>
        <h3>Biz haqimizda so'ngi yangiliklar</h3>
        <p>
          Bizdagi so’ngi o‘zgarishlar va yangiliklarni saytimiz yoki ijtimoiy
          tarmoqlarimiz <br />
          orqali kuzatib boring
        </p>
      </div>
      <div class="body">
        <div class="body-news">
          <img src="src/assets/images/people.svg" alt="" />
          <button>Yangilik</button>
          <h4>
            UA Technologiesda biznesni avtomatlashtirish , bo’yicha maxsus
            masterklas bo’lib o’tdi
          </h4>
          <p>
            Masterklassda kompaniya hodimlari uchun maxsus mehmon tomonidan <br>
            yangi bilim va ko’nikmalar berildi.
          </p>
          <button>Batafsil</button>
        </div>
        <div class="body-card">
          <div class="card-ux-li">
            <img src="src/assets/images/ux-li.svg" alt="" />
            <div>
              <h4>
                UA Technologiesda junior, middle UI/UX dizayner bo’lish
                imkoniyati bor!
              </h4>
              <p>
                O’z qilgan ishlaringiz va dizaynlaringizni maxsus link orqali
                jo’nating va...
              </p>
            </div>
          </div>
          <div class="card-contract">
            <img src="src/assets/images/contract.svg" alt="" />
            <div>
              <h4>
                Jamoa yangi hamkorlar bilan ikki tomonlama kelishuvga qo’l
                qo’ydi
              </h4>
              <p>Bugun ofisimizda yangi hamkorlar bilan uchrashuvda....</p>
            </div>
          </div>
          <div class="card-people">
            <img src="src/assets/images/hundred.svg" alt="" />
            <div>
              <h4>UA Technologies jamoasi hodimlar soni 100dan ortdi!</h4>
              <p>UA Technologies jamoasi soni kundan kunga kengaymoqda....</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>


<style scoped>
.body {
  display: flex;
  width: 85%;
  margin: 100px auto;
}
.header {
  text-align: center;
  color: white;
  margin-bottom: 40px;
}

.header-start {
  display: flex;
  text-align: center;
  justify-content: center;
  height: 50px;
  align-items: center;
  margin-top: 60px;
  color: white;
}

.header-start h5 {
  font-size: 17px;
  color: #7f43ff;
}

.header-start h6 {
  margin-left: 10px;

  font-size: 17px;
}

.body-news img {
  display: block;
  margin-bottom: 20px;
}
.body-news img:hover {
  transform: scale(1.01);
}
.body-news button:nth-child(2) {
  background: yellow;
  border: none;
  padding: 4px 20px;
  border-radius: 20px;
  margin: 10px 0;
}
.body-news button:nth-child(2):hover {
  transform: scale(1.04);
    cursor: default;

}
.body-news{
  color: white;
}
.body-news button:nth-child(5) {
  border: none;
  border-bottom: 1px solid grey;
  background: transparent;
  color: grey;
}
.body-news button:nth-child(5):hover {
  color: white;
  transform: rotateX("20deg");
  transition: 0.3s;
  border-bottom: 2px solid white;
  transform: scale(1.1);
  cursor: default;
}
.body-card h4 {
  color: white;
  font-size: 19px;
}

.card-ux-li {
  display: flex;
  font-size: 16px;
  align-items: center;
  gap: 30px;
  margin-bottom: 20px;
}
.card-ux-li:hover{
  transform: scale(1.02);
    cursor: pointer;
}
.card-contract {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 20px;
}
.card-contract:hover{
    transform: scale(1.02);
      cursor: pointer;
}

.card-people {
  display: flex;
  align-items: center;
  gap: 10px;
   margin-bottom: 20px;
}
.card-people:hover{
   transform: scale(1.02);
   cursor: pointer;
}
 @media only screen and (max-width: 840px){
     .body{
      display:block;
     }
     .body-news{
      margin-bottom: 20px;
     }
    }
</style>










