<template>
  <div class="header">
      <div class="header__left">
          <h1 class="header__title" >HELLO!!!</h1>
          <h1 class="header__title" >WE ARE CREATIVE</h1>
          <h1 class="header__title" >DIGITAL AGENCY</h1>
          <p class="header__text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Praesentium in aut ex dicta ab! Reiciendis.</p>
          <button class="header__btn btn">SEND MESSAGE</button>
      </div>
      <div class="header__right">
          <img src="@/assets/images/header.jpg" alt="" class="header__img">
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.header{
    display: grid;
    grid-template-columns: repeat(2,1fr);
    margin-top: 50px;
}

.header__left{
    padding: 60px 0;
}

.header__title{
    font-weight: bolder;
    font-size: 43px;
    margin-top: 10px;
}

.header__text{
    margin-top: 30px;
    font-size: 20px;
}
</style>