<template>
  <div class="card">
    <div class="document">
      <div class="">
        <div class="card-all">
          <div class="image-people">
            <img :src="cardlink" alt="" />
          </div>
          <img :src="logo" alt="" />
          <h3>{{ comment }}</h3>
          <h5>{{ name }}</h5>
          <p>{{ career }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
defineProps({
  cardlink: String,
  logo: String,
  comment: String,
  name: String,
  career: String,
});
</script>

<style  scoped>
.document {
  color: white;
  text-align: center;
}
.document .card-all {
  position: relative;
  margin: 70px 0 0px 0;
  line-height: 70px;
  letter-spacing: 1px;
  border-radius: 30px;
}

.image-people {
  position: absolute;
  top: -120px;
  left: 36%;
}
.card {
  background-color: rgb(32, 37, 30);
  margin-top: 120px;
}
.card:hover {
  transform: scale(1.02);
  cursor: pointer;
}
 @media only screen and (max-width: 840px){
     .image-people{
      position: absolute;
   left: 29%;
      }
      .image-people img{
    min-width: 1px;
      }
    }
</style>