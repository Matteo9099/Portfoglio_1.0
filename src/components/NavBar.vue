<template>
    <div>
        <input type="checkbox" id="active">
        <label for="active" class="menu-btn"><i class="fas fa-bars animate__animated animate__flipInX"></i></label>
        <div class="wrapper">
            <ul>
                <li v-for="navLink in navLinks" :key="navLink.routeName">
                    <router-link class="navLink" :to="{ name: navLink.routeName }">{{navLink.label}}</router-link>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'navBar',
    data() {
        return{
            navLinks: 
            [
                { routeName: 'home', label: 'Home' },
                { routeName: 'about', label: 'Chi sono' },
                { routeName: 'curriculum', label: 'Curriculum' },
                { routeName: 'contact', label: 'Contatti' },
            ]
        }
    }
}
</script>

<style scoped>
@import '../assets/style/navbar.scss';

.wrapper .navLink{
    color: none;
    text-decoration: none;
    font-size: 30px;
    font-weight: 500;
    padding: 5px 30px;
    color: #fff;
    border-radius: 50px;
    background: #000;
    position: relative;
    line-height: 50px;
    transition: all 0.3s ease;
}

  .navLink:after{
    position: absolute;
    content: "";
    background: #fff;
     background: linear-gradient(#14ffe9, #ffeb3b, #ff00e0);
    /*background: linear-gradient(375deg, #1cc7d0, #2ede98);*/
    width: 104%;
    height: 110%;
    left: -2%;
    top: -5%; 
    border-radius: 50px;
    transform: scaleY(0);
    z-index: -1;
    animation: rotate 1.5s linear infinite;
    transition: transform 0.3s ease;
  }
  .router-link-active:hover:after{
    transform: scaleY(1);
  }
  .router-link-active:hover{
    color: #fff;
  }

</style>