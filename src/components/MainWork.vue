<template>
  <div class="main__work">
      <h1 class="main__work-title title">WORK SNOWCASE.</h1>
      <div class="main__work-links">
          <ul class="main-links">
              <li>ALL</li>
              <li>BRANDING</li>
              <li>ILLUSTRATION</li>
              <li>WEB</li>
          </ul>
          <form action="">
              <select class="main__list" name="" id="">
                  <option><a href="#!">NEWEST FIRST</a></option>
                  <option><a href="#!">NEWEST SECOND</a></option>
                  <option><a href="#!">NEWEST THIRD</a></option>
                  <option><a href="#!">NEWEST FOURTH</a></option>
              </select>
          </form>
      </div>
      <div class="main__work-content">
          <div class="imgs1">
            <div class="img1">
                <h2>ARTWORK</h2>
                <p>BRANDING</p>
            </div>
            <img class="img2" src="@/assets/images/big1.jpg" alt="">
          </div>
          <div class="imgs2">
            <img class="img4" src="@/assets/images/big2.jpg" alt="">  
            <img class="img3" src="@/assets/images/mini2.jpg" alt="">
          </div>
          <div class="imgs3">
            <img class="img5" src="@/assets/images/mini3.jpg" alt="">
            <img class="img6" src="@/assets/images/big3.jpg" alt="">  
          </div>
      </div>
      <button class="main__btn btn">SEND MESSAGE</button>
  </div>
</template>

<script>
export default {

}
</script>

<style>


.main__work{
    margin-top: 70px;
}

.main__work-links{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 25px;
}

.main-links{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
}

.main-links li{
    transition: 0.4s;
    padding: 4px;
    cursor: pointer;
}

.main-links li:hover{
    background: yellow;
}

.img1{
    height: 290px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 20px;
    background: yellow;
}

.imgs1{
    display: flex;
    flex-direction: column;
    row-gap: 15px;
}

.imgs2{
    display: flex;
    flex-direction: column;
    row-gap: 15px;
}

.imgs3{
    display: flex;
    flex-direction: column;
    row-gap: 15px;
}

.main__work-content{
    display: flex;
    column-gap: 15px;
    margin-top: 30px;
}

.main__list{
    border: none;
    outline: none;
}

.main__btn{
    margin: 30px auto 0 auto;
    display: block;
}

</style>