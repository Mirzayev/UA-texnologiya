<template>
  <div class="container">
    <div class="">
      <div class="header">
        <div class="header-start">
          <h5>
            04 |
            <h6>Mijoz fikri</h6>
            <hr />
          </h5>
        </div>
        <div class="header-finish">
          <div><img src="src/assets/images/thought-card.png" alt="" /></div>
          <div>
            <h3>Mijozlarimizning bizga nisbatan iliq fikrlari</h3>
            <p>
              Mijozlarimiz bizni natijalarimiz, samimiy xizmatimiz, sohaviy
              bilimimiz va loyihalarni o'z vaqtida yetkazib berishimizdan doim
              mamnun. Bu yerda ba’zi mijozlarimizning bizga nisbatan fikrlari:
            </p>
          </div>
        </div>
      </div>
      <div class="body"></div>
    </div>
    <div class="card-famous container">
      <TeamCard
        class="CardPeople"
        v-for="item in famPeople"
        :key="item"
        :cardlink="item.CardLink"
        :logo="item.logo"
        :comment="item.comment"
        :name="item.name"
        :career="item.career"
      />
    </div>
    <div class="contact">
      <h1>Biz bilan bog'laning!</h1>
      <div class="InputPart">
        <div class="inputs">
            
          <ContactUs placeholder="ism familiya" :img="card1"/>
            <!-- <template #user>
              <div>
                <img :src="card1" alt="" />
                <p>nsdhf</p>r
              </div>
            </template> -->

            <!-- <template #email>
              <img :src="card2" alt="" />
            </template> -->
          
          <ContactUs :img="card2" placeholder="Elektron manzil" />
          <ContactUs :img="card3" placeholder="Telefon raqam" />
          <!-- <ContactUs :img="card4" placeholder="Qisqacha loyihangiz haqida yozing" /> -->
          <label class="textarea" for="">
            <img src="src/assets/images/chat.png" alt="" />
            <textarea
              name=""
              id=""
              placeholder="Qisqacha loyihangiz haqida yozing"
            ></textarea>
          </label>
          <br />
          <button class="button">Jo'natish</button>
        </div>
        <div class="input-card">
          <img src="src/assets/images/input-card.png" alt="" />
        </div>
      </div>
    </div>
  </div>
  <FooterPart />
</template>

<script setup>
import TeamCard from "@/components/TeamCard.vue";
import ContactUs from "./InputValue.vue";
import FooterPart from "./FooterPart.vue";
const famPeople = [
  {
    CardLink: "src/assets/images/Famous-1.png",
    logo: "src/assets/images/strength.png",
    comment: "Top Jamoa! Natija super.",
    name: "Javohir K.",
    career: "Direktor",
  },
  {
    CardLink: "src/assets/images/Famous-2.png",
    logo: "src/assets/images/strength.png",
    comment: "Shubhasiz barchaga tavsiya qilaman!",
    name: "Mavluda A. ",
    career: "Bosh Menedjer",
  },
  {
    CardLink: "src/assets/images/Famous-3.png",
    logo: "src/assets/images/strength.png",
    comment: "Rahmat! Jamoa ishlari juda yoqdi.",
    name: "Karimjon N.",
    career: "Menedjer",
  },
];

const card1 = "src/assets/images/user-name.png";
const card2 = "src/assets/images/email.png";
const card3 = "src/assets/images/phone.png";
const card4 = "src/assets/images/chat.png";
</script>

<style  scoped>
.header-start {
  display: flex;
  height: 40px;
  align-items: flex-end;
  gap: 10px;
}
.header-start h5 {
  margin-left: 120px;
  color: yellow;
}
hr {
  width: 40%;
}

.header-finish {
  display: flex;
  width: 50%;
  color: white;
  margin: 40px;
}
.header-finish h3 {
  font-size: 35px;
}
.inputs {
  width: 70%;
}
.card-famous {
  gap: 20px;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  text-align: center;
  justify-content: center;
  max-width: 1120px !important;
  margin: 0 auto;
}
.contact {
  margin-top: 50px;
  width: 94%;
  margin: auto;
  gap: 30px;
}

.InputPart {
  display: flex;
  justify-content: center;
}
.InputPart textarea {
  display: flex;
  align-items: center;
  background: rgba(22, 30, 37, 1);
  border: none;
  padding-bottom: 120px;
  height: 100%;
  margin-top: 20px;
  gap: 40px;
  width: 100%;
}
.contact h1 {
  color: white;
  /* margin: 100px 0 30px 100px; */
}
.inputs img {
  margin-top: 20px;
  padding-left: 12px;
}

textarea:focus {
  outline: none;
  color: white;
}
.textarea {
  display: flex;
  margin-top: 10px;
  background: rgba(22, 30, 37, 1);
  align-items: flex-start;
  color: white;
  gap: 12px;
  border-radius: 10px;
}
textarea::placeholder {
  color: white;
}
.textarea:hover {
  transform: scale(1.02);
}
.button {
  margin-top: 20px;
  background: rgba(36, 21, 112, 1);
  padding: 3px 20px;
  color: white;
  border-radius: 20px;
  border: none;
}
.input-card img {
  width: 100%;
}
.button:hover {
  transform: scale(1.05);
}

@media only screen and (max-width: 840px) {
  .CardPeople {
    display: block;
  }
  .header-start h5 {
    font-size: 15px;
  }
  .InputPart {
    display: block;
    width: 100%;
  }
  .input-card img {
    width: 100%;
  }
  .inputs {
    width: 100%;
  }
}
</style>

























