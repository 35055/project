<template>
  <div class="main__our">
      <h1 class="main__our-title title">OUR BLOG.</h1>
      <p class="main__our-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi similique praesentium commodi consequuntur, nostrum incidunt. Aspernatur impedit recusandae expedita excepturi.</p>
      <div class="main__our-content">
          <div class="main__our-info">
              <div class="ourBlock">
                  <h2 style="font-size: 30px;">READ MORE</h2>
              </div>
              <h3 style="padding: 0 20px;">SUPER BLOG ARTICLE!</h3>
              <p style="font-size:12px; padding: 0 20px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum, placeat?</p>
              <p style="font-size:12px; padding:0 25px;">20 May 2020</p>
          </div>
          <div class="main__our-info">
              <img src="@/assets/images/our1.webp" style="max-width:290px; mah-height:290px;" alt="" class="main__our-img">
              <h3 style="padding: 0 20px;">SUPER BLOG ARTICLE!</h3>
              <p style="font-size:12px; padding: 0 20px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum, placeat?</p>
              <p style="font-size:12px; padding:0 25px;">20 May 2020</p>
          </div>
          <div class="main__our-info">
              <img src="@/assets/images/our2.jpg" style="max-width:290px; mah-height:290px;" alt="" class="main__our-img">
              <h3 style="padding: 0 20px;">SUPER BLOG ARTICLE!</h3>
              <p style="font-size:12px; padding: 0 20px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum, placeat?</p>
              <p style="font-size:12px; padding:0 25px;">20 May 2020</p>
          </div>
      </div>
  </div>
</template>

<script>
export default {}
</script>

<style>

.ourBlock{
    background: yellow;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 290px;
    height: 290px;
}

.main__our-info{
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.main__our-content{
    display: grid;
    grid-template-columns: repeat(3,1fr);
    gap: 15px;
    margin-top: 50px;
}


.main__our{
    margin-top: 90px;
}

.main__our-text{
    max-width: 700px;
    width: 100%;
    margin-top: 20px;
    font-size: 15px;
}
</style>