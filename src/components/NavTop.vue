<template>
  <div id="top" class="nav">
      <img src="@/assets/images/logo.png" alt="" class="nav__img">
      <ul class="nav__links">
          <li>WORK</li>
          <li>ABOUT</li>
          <li>BLOG</li>
          <li>CONTACT</li>
      </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.nav{
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 40px;
}

.nav__links{
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 60px;
}

.nav__links li{
  cursor: pointer;
}

.nav__img{
  width: 80px;
  height: 80px;
}
</style>