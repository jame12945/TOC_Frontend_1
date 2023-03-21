<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
      
    <div class="grid-container">
    <div>
      <div class="circle" ><img src= "https://scontent.xx.fbcdn.net/v/t1.15752-9/334414947_1375856073209787_1540111623284317173_n.jpg?stp=dst-jpg_p370x247&_nc_cat=102&ccb=1-7&_nc_sid=aee45a&_nc_ohc=04ZIhrs_drYAX-nEKhQ&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AdTdUCPuCzAIUFM2faJMD9WAMWJS3x-hIykMTZbXyLPqiA&oe=6440BF8B" alt="person1" width="200" height="200"></div>
    <h3>ชื่อ:ทิวัตถ์ โพธิ์ศรี</h3>
    <p class="jobmember">หน้าที่: Frontend</p>
    </div>
    <div>
      <div class="circle"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Frontend</p>
    </div>
    <div>
      <div class="circle"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Frontend</p>
    </div>
  </div>
  <div class="grid-container">
    <div>
      <div class="circle"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Frontend</p>
    </div>
    <div>
      <div class="circle"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Frontend</p>
    </div>
    <div>
      <div class="circle"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Frontend</p>
    </div>
  </div>
  <div class="grid-container">
    <div>
      <div class="circle2"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Backend</p>
    </div>
    <div>
      <div class="circle2"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Backend</p>
    </div>
    <div>
      <div class="circle2"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Backend</p>
    </div>
  </div>
  <div class="grid-container2">
    <div>
      <div class="circle2"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Backend</p>
    </div>
    <div>
      <div class="circle2"></div>
      <h3>ชื่อ:--------------------</h3>
    <p class="jobmember">หน้าที่: Backend</p>
    </div>
    
    </div>
    
    


  

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
.circle {
  height: 200px;
  width: 200px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  gap: 50px;
}
.circle2 {
  height: 200px;
  width: 200px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  gap: 50px;
}
.circle:hover{
  filter: drop-shadow(0 0 2em #07f21baa);
}
.circle2:hover{
  filter: drop-shadow(0 0 2em #ff0f57aa);
}
.grid-container {
  border: none;
  background-color: transparent;
  display: grid;
  grid-template-columns: auto auto auto;
  gap: 80px;
}
.grid-container > div {
  border: none;
  background-color: transparent
}
.grid-container2{
margin-left: 14%;
display: grid;
grid-template-columns: auto auto auto;
gap: 80px;
}
.jobmember{
margin-top: -20px;

}
img{
  border-radius: 80%;
}

</style>
