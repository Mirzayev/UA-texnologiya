<template>
  <div class="service-card-child">
    <div class="sayt-icon">
      <h2>{{ nomi }}</h2>
      <img :src="img" alt="" class="" />
    </div>

    <h5 class="card-body">{{ name }}</h5>
  </div>
</template>

<script setup>
defineProps({
  nomi: String,
  id: Number,
  name: String,
  img: String,
  });
  </script>

  <style scoped>
.service-card-child {
  background-color: rgba(26, 16, 80, 1);
  border-radius: 8px;
  padding: 24px 32px;
  color: white;
}
.sayt-icon {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.service-card-child:hover {
  transform: scale(1.01);
}

.card-body {
  font-size: 16px;
  font-weight: 400;
  line-height: 21px;
}
</style>
















