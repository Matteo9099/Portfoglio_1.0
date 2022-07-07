<template>

    <div>

        <NavBar></NavBar>

        <div class="container-cv">
            <!-- COMPETENZE -->
            <div class="subContainer">
                <h2 class="skills-title animate__animated animate__fadeIn">Competenze</h2>
                <div class="skills-element">
                    <img src="../assets/img/elemnt/html.png" class="animate__animated animate__fadeInUp delay02" alt="html_element">
                    <img src="../assets/img/elemnt/css.png" class="animate__animated animate__fadeInUp delay04" alt="css_element">
                    <img src="../assets/img/elemnt/javascript.png" class="animate__animated animate__fadeInUp delay06" alt="js_element">
                    <img src="../assets/img/elemnt/php.png" class="animate__animated animate__fadeInUp delay08" alt="php_element">
                    <img src="../assets/img/elemnt/vue.png" class="animate__animated animate__fadeInUp delay10" alt="vue_element">
                    <img src="../assets/img/elemnt/laravel.png" class="animate__animated animate__fadeInUp delay12" alt="laravel_element">
                    <img src="../assets/img/elemnt/bootstrap.png" class="animate__animated animate__fadeInUp delay14" alt="bootstrap_element">
                    <img src="../assets/img/elemnt/java.png" class="animate__animated animate__fadeInUp delay16" alt="java_element">
                    <img src="../assets/img/elemnt/mySql.png" class="animate__animated animate__fadeInUp delay18" alt="mysql_element">
                    <img src="../assets/img/elemnt/git.png" class="animate__animated animate__fadeInUp delay20" alt="git_element">
                    <img src="../assets/img/elemnt/github.png" class="animate__animated animate__fadeInUp delay22" alt="github_element">
                </div>
            </div>
            <!-- FORMAZIONE -->
            <div class="subContainer">
                <h2 class="skills-title" data-aos="fade-up">Formazione</h2>
                <div class="formation">
                    <div class="d-flex" data-aos="fade-up">
                        <h4 class="subTitle">Boolean Carrers</h4>
                        <span class="subSpan">Novembre 2021 - Maggio 2022</span>
                    </div>
                    <p class="subProf"  data-aos="flip-left">Full Stack Web Developer</p>
                    <p class="subText" data-aos="zoom-in-up">Il corso di Boolean per Full Stack Developer è full-time dal lunedi al venerdi per 6 mesi, un totale di 700 ore tra teoria e pratica. Ho imparato ad utilizzare linguaggi e framework di come riportato nelle competenze, costruire siti web responsive, aggiungere interazioni alle pagine web, interrogare i database, creare applicazioni web</p>
                </div>
                <!-- SECOND -->
                <div class="formation">
                    <div class="d-flex" data-aos="fade-up">
                        <h4 class="subTitle">Istituto Volta</h4>
                        <span class="subSpan">Ottobre 2020 - Ottobre 2021</span>
                    </div>
                    <p class="subProf"  data-aos="flip-left">Oracle Java Programmer</p>
                    <p class="subText" data-aos="zoom-in-up">Nel corso di ore 88 per il linguaggio Java ho acquisito competenze nella programmazione modulare in particolare: - Tipi di dati primitivi - stringhe - operatori e costrutti decisionali - Usare classi, oggetti ed array - Ereditaietà ed Interfacce - Lavorare con Arrays e Collections - Manipolare le eccezzioni</p>
                </div>
            </div>
          
            <!-- ESPERIENZE PROFESSIONALI -->
            <div class="subContainer">
                <h2 class="skills-title" data-aos="fade-up">Esperienze</h2>
                <div class="formation">
                    <div class="d-flex" data-aos="fade-up">
                        <h4 class="subTitle">Boolean Carrers</h4>
                        <span class="subSpan">Novembre 2021 - Maggio 2022</span>
                    </div>
                    <p class="subProf"  data-aos="flip-left">Full Stack Web Developer</p>
                    <p class="subText" data-aos="zoom-in-up">Realizzazione partendo da zero di applicazioni web complete di Backend e Frontend responsive. Alcune repliche di progetti svolti come Netflix, Whatsapp Web, Spotify Web, Discord ecc...</p>
                    <div class="d-flex" data-aos="fade-up">
                        <h4 class="subTitle">Altro settore</h4>
                        <span class="subSpan">Novembre 2018 - Novembre 2021</span>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<script>
import NavBar from '../components/NavBar.vue'
export default {
    name: "CvVitae",
    data() {
        return {
            skillImg: [
                { srcName: "../assets/img/elemnt/html.png", altName: "HTML" },
                { srcName: "../assets/img/elemnt/html.png", altName: "HTML" }
            ]
        };
    },
    components: { NavBar }
}
</script>

<style>
@import '../assets/style/cv.scss';

</style>