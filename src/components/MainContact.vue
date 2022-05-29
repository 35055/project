<template>
  <div class="main__conctact">
    <h1 class="main__contact-title title" id="contact">CONTACT US.</h1>
    <p class="main__contact-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet officia quod tenetur aperiam impedit ut pariatur quis dicta ipsam quas?</p>
    <div class="main__contact-send">
      <div class="send-left">
        <h2 class="send-title">Send Us Message</h2>
        <input class="input" style="width:100%; padding:10px; margin-top: 20px;" type="text" placeholder="Name">
        <input class="input" style="width:100%; padding:10px;" type="mail" placeholder="E-mail">
        <textarea class="input" style="width:100%; resize: none; padding: 10px 0 60px 10px;" placeholder="Message"></textarea>
      </div>
      <div class="send-rigth">
        <img src="@/assets/images/contact1.webp" class="send-right-img" alt="">
      </div>
    </div>
    <div class="main__contact-icons">
      <div class="icon-item">
        <i class="fas fa-map-marker-alt"></i>
        <p>1211 Awesome Awenue</p>
        <p>My USD</p>
      </div>
      <div class="icon-item">
        <i class="far fa-mobile-android-alt"></i>
        <p>+00123 - 456 - 78</p>
        <p>+00123 - 456 - 78</p>
      </div>
      <div class="icon-item">
        <i class="fas fa-mailbox"></i>
        <p>bxndbdbvsj@gmail.com</p>
      </div>
    </div>
    <div class="main__contact-socialMedia">
      <i class="fab fa-facebook-f"></i>
      <i class="fab fa-twitter"></i>
      <i class="fal fa-basketball-ball"></i>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.main__contact-socialMedia{
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 35px;
  color: black;
  gap: 50px;
  margin-top: 50px;
}


.main__contact-icons{
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 100px;
  margin-top: 50px;
}

.icon-item{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  cursor: pointer;
}

.icon-item i {
  font-size: 35px;
  color: yellow;
  margin-bottom: 15px;
}

.icon-item p{
  font-size: 10px;
}

.input{
  background: rgba(234, 229, 229, 0.74);
  border-radius: 8px;
  border: none;
  outline: none;
}

.main__conctact{
  margin-top: 70px;
}

.send-left{
  display: flex;
  flex-direction: column;
  gap: 10px;
  padding: 60px 40px 0 0;
}


.main__contact-text{
  max-width: 700px;
  width: 100%;
  margin-top: 20px;
}


.main__contact-send{
  display: grid;
  grid-template-columns: repeat(2,1fr);
  margin-top: 40px;
}


.send-right-img{
  max-width: 450px;
  height: 450px;
  width: 100%;
}

</style>