<template>
  <div class="parent-card">
    <div class="container">
      <div class="ServiceStart">
        <h4>
          <h5>02 |</h5>
          Bizning xizmatlar
        </h4>
      </div>
      <div class="servicesThan">
        <h1>
          Xizmatlarimiz bilan keyingi <br />
          pog‘onaga chiqing!
        </h1>
      </div>

      <div class="service-card">
        <ServicesAboutVue
          class=""
          v-for="item in img"
          :key="item"
          :nomi="item.about"
          :name="item.name"
          :img="item.link"
        />
      </div>
    </div>
  </div>
</template>

<script setup>
import ServicesAboutVue from "./ServicesAbout.vue";

const img = [
  {
    link: "src/assets/images/www.png",
    about: "Veb-sayt",
    name: "Korporativ veb saytlardan tortib  veb ilovalargacha bo‘lgan murakkablikdagi internet saytlarni sifat kafolati bilan ishlab chiqamiz",
  },
  {
    link: "src/assets/images/crm.png",
    about: "CRM tizimlar",
    name: "Korporativ veb saytlardan tortib  veb ilovalargacha  bo‘lgan murakkablikdagi internet saytlarni sifat kafolati   bilan ishlab chiqamiz",
  },
  {
    link: "src/assets/images/icon-big.png",
    about: "Mobil ilovalar",
    name: "Istalgan qiyinchilikdagi mobil ilovalarni ishlab chiqish va ularni texnik qo‘llab-quvvatlash",
  },
  {
    link: "src/assets/images/star.png",
    about: "Logo va brending",
    name: "Biznesni ilgari surish uchun asosiy vositalar va marketing materiallari to‘plamini noldan yaratish",
  },
  {
    link: "src/assets/images/ux-li.png",
    about: "UI&UX dizayn",
    name: " Loyiha MindMap’ini ishlab chiqish va ushbu arxitektura asosida optimal yechimga ega dizaynlarni chizish",
  },
  {
    link: "src/assets/images/www.png",
    about: "Veb-sayt",
    name: "Korporativ veb saytlardan tortib  veb ilovalargachabo‘lgan murakkablikdagi internet saytlarni sifat kafolati bilan ishlab chiqamiz",
  },
];
</script>

<style  scoped>
.ServiceStart {
  margin-top: 50px;
  padding: 80px 0 20px 0;
  gap: 50px;
  text-align: center;
  justify-content: space-around;
}
h5 {
  display: inline-block;
  color: #7f43ff;
}
h4 {
  font-size: 19px;
}

h1 {
  color: white;
  padding-bottom: 40px;
}

.service-card {
  display: grid;
  grid-template-columns: repeat(2, 0.4fr);
  gap: 30px;
  justify-content: center;
}

.servicesThan {
  text-align: center;
}

.parent-card {
  background: rgba(15, 10, 43, 1);
}

    @media only screen and (max-width: 840px){
      h1{
        font-size: 20px;
      }
     
    }
</style>