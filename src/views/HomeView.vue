<template>
  <div class="home">

    <div class="hide-mobile mobile-tap-area">
      <div class="max-width">
        <div class="vertical-center">
          <h1>
            <div class="text-color-white hide-text-block">
              <div class="animate toggle-mobile-first">Ciao.</div>
            </div>
            <div class="text-color-red hide-text-block">
              <div class="animate delay04 toggle-mobile-first">Io sono</div>
            </div>
            <div class="text-color-red hide-text-block">
              <div class="animate delay08 toggle-mobile-first">Matteo</div>
            </div>
          </h1>
        </div>
      </div>
      <div class="tap-indication">Tap anywhere</div>
    </div>

    <div class="max-width">
      <div class="vertical-center">
        <h1>
          <div class="hide-text-block">
            <a href="about/">
              <div class="animate text-color-white on-hover-40 hide-web label-hello "></div>
              <div class="animate text-color-white on-hover-40 hide-mobile toggle-mobile-second">Chi sono</div>
            </a>
          </div>
          <div class="hide-text-block">
            <a href="curriculum/">
              <div class="animate text-color-red on-hover-40 delay04 hide-web label-iam"></div>
              <div class="animate text-color-red on-hover-40 delay04 hide-mobile toggle-mobile-second">Curriculum</div>
            </a>
          </div>
          <div class="hide-text-block">
            <a href="contact/">
              <div class="animate text-color-red on-hover-40 delay08 hide-web label-matteo"></div>
              <div class="animate text-color-red on-hover-40 delay08 hide-mobile toggle-mobile-second">Contatti</div>
            </a>
          </div>
        </h1>
      </div>
    </div>
    <div class="bg-photo"></div>

  </div>
</template>

<script>

export default {
  name: 'HomeView',  

}
</script>

<style>
@import '../assets/style/home.scss';
@import '../assets/style/font.scss';

</style>
