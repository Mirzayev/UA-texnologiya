  <template>
  <div class="container">
    <div class="contact">
      <label class="contact-label" for="">
        <img :src="img" alt="" />

        <slot name="user"/>
      
        <input class="contact-input" type="text " :placeholder="placeholder" />
         
       <slot name="email"/>

      </label>
        
    </div> 
  </div>

</template>

<script setup>
defineProps({
  img: String,
  placeholder: String,
});
</script>


<style  scoped>

.contact-label {
  display: flex;
  margin-top: 10px;
  /* width: 600px; */
  height: 85px;
 background: rgba(22, 30, 37, 1);
  align-items: center;
  color: white;
  gap: 10px;
  
}
.contact-label img{
  padding-left: 15px;
}
.contact-label:hover{
  /* transform: scale(1.02); */
}
.contact-input {
  background: transparent;
  border: none;
  width: 100%;
  height: 100%;
  color: aqua;
}
.contact-input:focus {
  border: none;
  outline: none;
}
.contact-input::placeholder {
  color: white;
}
</style>




