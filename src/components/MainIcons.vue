<template>
  <div class="main__icons">
      <div class="container">
          <img src="@/assets/icons/icon1.png" alt="" class="main__icon">
          <img src="@/assets/icons/icon2.png" alt="" class="main__icon">
          <img src="@/assets/icons/icon3.webp" alt="" class="main__icon">
          <img src="@/assets/icons/icon4.png" alt="" class="main__icon">
          <img src="@/assets/icons/icon5.webp" alt="" class="main__icon">
          <img src="@/assets/icons/icon6.webp" alt="" class="main__icon">
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.main__icons{
    margin-top: 80px;
}

.main__icons .container{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 60px;
}

.main__icons .container img{
    max-width: 100px;
    width: 100%;
}
</style>