<template>
  <div class="footer">
      <div class="footer__left">
        <img src="@/assets/images/logo.png" alt="">
        <p>Made by Murat</p>
      </div>
      <div class="footer__right">
        <a href="#top" class="footer-link">
            <p>BACK TO TOP</p>
            <i class="fas fa-angle-up"></i>
        </a>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.footer{
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-top: 80px;
    background: black;
    padding: 20px;
}


.footer-link{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 15px;
    color: white;
}

.footer__left{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
    color: white;
}

</style>