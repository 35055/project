<template>
  <div class="app">
    <div class="container">
      <NavTop/>
      <Header/>
      <MainWork/>
      <MainIcons/>
      <MainAbout/>
      <MainOur/>
      <MainContact/>
    </div>
      <Footer/>
  </div>
</template>

<script>

import NavTop from '@/components/NavTop.vue'
import Header from '@/components/Header.vue'
import MainWork from '@/components/MainWork.vue'
import MainIcons from '@/components/MainIcons.vue'
import MainAbout from '@/components/MainAbout.vue'
import MainOur from '@/components/MainOur.vue'
import MainContact from '@/components/MainContact.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'App',
  components: {
    NavTop,
    Header,
    MainWork,
    MainIcons,
    MainAbout,
    MainOur,
    MainContact,
    Footer
  }
}
</script>

<style>

</style>
