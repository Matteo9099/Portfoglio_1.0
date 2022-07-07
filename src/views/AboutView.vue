<template>
  <div class="about">

    <NavBar></NavBar>

    <div class="container">
   
        <img class="animate__animated animate__flash" src="../assets/img/laptop-2557466_1280-removebg-preview.png" alt="">
        <!-- <div class="about-name label-name on-hover-40 animate__animated animate__fadeInLeft delay02"></div>
        <div class="about-surname text-color-red label-surname on-hover-40 animate__animated animate__fadeInLeft delay04"></div> -->

        <!-- NAME -->
        <div class="d-flex wrap">
            <span class="spanName on-hover-40 animate__animated animate__lightSpeedInLeft">Matteo</span>
            <span class="spanName on-hover-40 animate__animated animate__lightSpeedInLeft">Morganti</span>
        </div>
        <!--PROFESSIONE  -->
        <div class="con-stack animate__animated animate__backInUp delay04">
            <span class="text-color-white on-hover-40">Jr Full Stack Web Developer</span>
        </div>

    </div>

      <div class="container-description">
          <p class="textContent animate__animated animate__fadeInUp delay10">Sono un Full Stack Web Developer Jr, verso metà 2020 mi appassiono all'informatica ed il mondo ITech, decido cosi di studiare tramite corsi e in modo autonomo. Acquisisco buone competenze come sviluppatore ( <span class="spanLink"><router-link style="color:#D1001D" to="/curriculum">vedi curriculum</router-link></span> ). Mi trovo a mio agio a lavorare soprattutto con Vue.js e Laravel</p>
      </div>
    
     
        <!-- FINE MODIFICHE -->

  </div>
</template>

<script>
import NavBar from '../components/NavBar';

export default {
  name: 'AboutView',
 
  components: {
    NavBar
  }

}
</script>

<style>
@import '../assets/style/home.scss';

</style>
