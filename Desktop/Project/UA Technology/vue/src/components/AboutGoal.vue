<template>
  <div class="parent bg-slate-600 w-96">
    <div class="mean ">
      <h1>
        Betakror raqamli
        <h2>yechimlarni</h2>

        taklif qilamiz !
      </h1>
      <button>Bog'lanish</button>
    </div>

    <div class="about">
      <p>
        Bizning xizmatlarimiz va loyihangiz bo'yicha yechimlarimiz biznesingiz
        uchun cheksiz imkoniyatlar yaratadi va har qanday g'oyalaringizni ilgari
        surishingiz uchun zaminlikni ta'minlaydi!
      </p>
    </div>
    <div class="batafsil">
      <span>
        <h3>Batafsilroq</h3>
        <img src="src/assets/images/logo.png" alt="" />
      </span>
    </div>
  </div>
</template>

<script>
</script>



<style scoped>
.parent {
  max-width: 1440px;
  width: 90%;
  margin: auto;
  text-align: center;
  justify-content: center;
  margin: auto;
  color: white;
}

.mean h1 {
  margin-top: 10px;
  font-size: 80px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.mean h2 {
  display: inline-block;
  color: #6243b1;

  font-size: 80px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

.mean {
  text-align: center;
}
.mean button {
  background-color: yellow;
  color: black;
  font-size: 14px;
  font-weight: 700;
  width: 90px;
  height: 30px;
  border-radius: 20px;
  margin: 40px 0 0 20px;
  padding: 5px 10px;
  border: none;
  margin-bottom: 40px;
  transition: 0.3s;
}
.mean button:hover {
  background-color: rgb(187, 187, 68);
  transform: scale(1.05);
}
.about {
  box-shadow: -4px -20px 40px -4px rgb(84, 23, 159);
  display: flex;
  border-radius: 10px;
  text-align: center;
  font-size: 20px;
  padding: 10px 60px;
  background-color: rgb(21, 21, 80);
}
.about p {
  background-color: rgb(21, 21, 80);
  border-radius: 10px;
}

.batafsil {
  margin: 40px 0;
  text-align: center;
}
.batafsil h3{
  color: grey;
}

.batafsil h3:hover {
  color: white;
}
.batafsil img:hover {
  color: rgb(17, 183, 234);
}

@media only screen and (max-width: 1050px) {
  .mean h1 {
    font-size: 65px;
  }
  .mean h2 {
    font-size: 65px;
  }
  
  }

@media only screen and (max-width: 840px) {
  .mean {
    margin-top: 60px;
  }


  .mean h1 {
    font-size: 50px;
  }
  .mean h2 {
    font-size: 50px;
  }
  p {
    font-size: 15px;
  }
  .mean button{
    padding: 0;
    font-size: 12px;
    width: 80px;
  }

  h3 {
    font-size: 16px;
    margin: 0;
    padding: 0;
  }
}
@media only screen and (max-width: 450px) {
  p{
    font-size: 12px;
  }
  .batafsil img{
    width: 20px;
  }
.about{
  padding: 0;
  margin: 0;
  padding: 10px 15px;
}
 .mean h1 {
    font-size: 40px;
  }
  .mean h2 {
    font-size: 40px;
  } 
}
@media only screen and (max-width: 360px) {

 .mean h1 {
    font-size: 30px;
  }
  .mean h2 {
    font-size: 30px;
  } 
}

</style>















