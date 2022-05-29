<template>
  <div class="main__about">
      <div class="container">
          <h1 class="main__about-title title">ABOUT US.</h1>
          <p class="main__about-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti natus animi possimus nulla odio neque ab maxime, dolorum eum iure illum aut, ad ipsam at.</p>
          <div class="main__about-content imgAbout">
              <img src="@/assets/images/about2.jpeg" alt="" class="main__about-img">
              <div class="imgAbout-info">
                  <h3 style="font-size:15px;">Luke Skaywalker</h3>
                  <p style="font-size:10px; color: white;">Web Designer</p>
              </div>
              <img src="@/assets/images/about1.jpg" alt="" class="main__about-img">
              <div class="imgAbout-info2">
                  <h3 style="font-size:15px;">Luke Skaywalker</h3>
                  <p style="font-size:10px; color: white;">Web Designer</p>
              </div>
              <div class="main__about3">
                  <h2 class="main__about3-title">Little About Us</h2>
                  <p class="main__about3-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Repudiandae nesciunt iste unde sed fugit beatae. Fugit quidem natus perspiciatis in.</p>
                  <a href="#!" class="main__about3-link">Read More</a>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.main__about{
    margin-top: 100px;
}

.main__about-text{
    max-width: 700px;
    margin-top: 30px;
}

.main__about-content{
    margin-top: 30px;
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 15px;
}

.main__about-img{
    max-width: 290px;
    width: 100%;
}

.imgAbout{
    position: relative;
}

.imgAbout-info{
    position: absolute;
    background: yellow;
    max-width: 180px;
    width: 100%;
    top: 30;
    bottom: 0;
    left: 0;
    padding: 10px;
}

.imgAbout-info2{
    position: absolute;
    background: yellow;
    max-width: 180px;
    width: 100%;
    bottom: 0;
    left: 305px;
    padding: 10px;
}

.main__about-text{
    font-size: 20px;
}

.main__about3{
    padding: 100px 25px;
    display: flex;
    gap: 20px;
    flex-direction: column;
}

.main__about3-title{
    font-size: 30px;
}

.main__about3-text{
    font-size: 15px;
}

</style>