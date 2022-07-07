<template>
    <div class="paddingBot">
        <NavBar></NavBar>

        <div class="container">
            <div class="contact-title animate__animated animate__fadeIn">L'unico posto in cui il successo arriva prima del lavoro è nel dizionario.</div>
            <author class="contact-author animate__animated animate__fadeInUp dalay18">Vince Lombardi</author>
        </div>
        <!-- SEZIONE CONTATTI -->
       <div class="container-description">
            <div class="contact text-color-red animate__animated animate__wobble delay20">Contatti</div>
            <p class="textContent" data-aos="fade-up">Cerco opportunità per collaborare ed entrare in aziende/startup, crescere di più in ambito professionale e personale. <br>Voglio evitare contatti non inerenti al tipo di lavoro svolto, ciò non esclude imparare nuove teconologie, di cui sono a favore se fatto nel modo corretto.</p>
            <div class="contact-platform text-color-red" data-aos="fade-up">Sentiti libero di contattarmi su una delle mie piattaforme</div>
       </div>
       <!-- SOCIAL -->
       <div class="container-social" data-aos="fade-up">
            <div id="email" title="invia email"><a href="mailto:matteo99morganti@gmail.com" class="text-color-white">matteo99morganti@gmail.com</a></div>
            <div id="linkedln" title="Vai a linkedln"><a href="https://www.linkedin.com/in/matteo-morganti-developer" class="text-color-white">Linkedln</a></div>
            <div id="github" title="vai a GitHub"><a href="https://github.com/Matteo9099?tab=repositories" class="text-color-white">GitHub</a></div>
       </div>

    </div>
</template>

<script>
import NavBar from '../components/NavBar.vue';

export default {
    name: "ContactView",
    components: { NavBar }
}
</script>

<style>
@import '../assets/style/home.scss';

</style>