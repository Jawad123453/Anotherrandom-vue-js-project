<template>
  <div class="card">
    <div class="img-holder">
      <img src="../imgs/img1.jpg" alt="">
    </div>
    <div class="card-text">
      <h1>Jawad Alhajj</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium nam nulla ea dolore reiciendis ipsum vero repellat at deserunt rerum voluptate .</p>
    </div>
  </div>
</template>

<script setup>
  await new Promise((res) =>setTimeout(res,2000))
</script>

<style>
.card{
  display: flex;
  align-items: center;
  gap:20px;
  padding:10px;
  background-color: rgb(209, 209, 209);
  box-shadow: 0px 0px 10px 0px rgb(88, 88, 88);
  width:600px;
  margin:20px auto;
}
.card .img-holder{
  width:150px;
  height:150px;
}
.card-text{
  display:flex;
  flex-direction: column;
  gap:20px;
}
.card .img-holder img{
  width:100%;
  height:100%;
  border-radius: 50%;
  border: none;
}
.card .card-text h1{
  font-weight: bold;
}
.card .card-text p{
  width:400px;
  line-height: 1.5;
}
</style>