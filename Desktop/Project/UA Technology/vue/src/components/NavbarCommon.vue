<template>
  <div class="container">
    <div class="parent">
      <div class="katta-div">
        <div class="navbar bg-slate-700">
          <div class="logo bg-slate-700">
            <img class="bg-slate-700" src="public/Group.png" alt="images" />
          </div>
          <div class="menu bg-slate-700 ">
            <div class="menu-name bg-slate-700 text-white hover:text-red">
              <h3 class=" bg-transparent">Asosiy</h3>
              <h3 class=" bg-transparent">Biz haqimizda</h3>
              <h3  class=" bg-transparent">Xizmatlar</h3>
              <h3 class=" bg-transparent">Blog</h3>
            </div>

            <div class="background-select bg-transparent text-white" >
              <select name="" id="">
                <option value="">Uzb</option>
                <option value="">Rus</option>
                <option value="">Ing</option>
              </select>
              <button>Bog'lanish</button>
            </div>
          </div>
          <img  class="menu-icon" src="src/assets/images/menu-icon.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>
 



<script setup>
</script>

 

<style scoped>
.navbar {
  max-width: 1440px;
  width: 100%;
  text-align: center;
  display: flex;
  flex-wrap: wrap;
  height: 70px;
  align-items: flex-end;
  justify-content: space-around;
  margin-top: 20px;
}
.navbar img:nth-child(3) {
  display: none;
}
.menu {
  display: flex;
  align-items: center;
  gap: 40px;
}
.menu img {
  display: none;
}
.menu-name {
  display: flex;
  gap: 20px;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}

.menu-name h3 {
  font-size: 16px;
}
.menu-name h3:hover {
  color: white;
  cursor: pointer;
  transition: 0.4s;
}
.background-select {
  gap: 20px;
}
.background-select select {
  font-size: 16px;
  padding: 2px 5px;
  border-radius: 8px;
}
.background-select select:click {
  outline: none;
}
.background-select button {
  background-color: yellow;
  color: black;
  /* font-size: 13px; */
  font-weight: 700;
  width: 90px;
  height: 30px;
  border-radius: 20px;
  margin-left: 10px;
  border: none;
  transition: 0.3s;
}
.background-select button:hover {
  background-color: rgb(187, 187, 68);
  transform: scale(1.05);
}
.background-select button:active {
  background-color: rgb(118, 93, 93);
  color: rgb(250, 245, 245);
  transition: 0.01s;
}

 @media only screen and (max-width: 870px) {
  .navbar img:nth-child(3) {
    display: block;
    
  }
   .logo img{
    width: 80%;
  }
  .menu-icon{
    width: 3%;
    min-width: 24px;
  }
  .background-select {
    display: none;
  }
    .menu-name h3 {
    display: none;
    
  }
 }
  @media only screen and (max-width: 600px){
.menu-icon{
    width: 5px;
  }
  
  .logo img{
    width: 80%;
    min-width: 200px;
  }
  .navbar {
    display: flex;
    height: 50px;
    align-items: center;
    
  }
  .logo {
    margin-top: 10px;
    
  }



  .navbar img {
    flex-wrap: wrap;
    padding: 0;
    margin: 0;
  }
  
  }
  @media only screen and (max-width: 400px){
    .navbar{
      display: flex;
      justify-content: center;
    }
  .menu-icon{
    margin-top: 200px;
    width: 20px;  
  }
  
  }
</style>















