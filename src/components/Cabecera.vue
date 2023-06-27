
<template>
    <div class="header">
        <div class="navbar">
            <div class="navbar__logo">
                <img src="../assets/img/logo.svg" alt="">
            </div>
            <div class="navbar__options">
                <div class="navbar__box">
                    <p>Colecciones</p>
                </div>
                <div class="navbar__box">
                    <p>Ofertas</p>
                </div>
                <div class="navbar__box">
                    <p>Nueva Llegada</p>
                </div>
                <div class="navbar__box">
                    <p>Lo mas vendido</p>
                </div>
                <div class="navbar__box">
                    <p>Fajas</p>
                </div>
            </div>

            <div class="navbar__icons">
                <div class="navbar__iconsBox">
                    <img src="" alt="">
                </div>
                <div class="navbar__iconsBox">
                    Discord
                </div>
                <div class="navbar__iconsBox">
                    Twitter
                </div>
                <div class="navbar__iconsBox">
                    Medium
                </div>
            </div>
            <!-- <div>
                <button flat>Login</button>
                <button>Get Started</button>
            </div> -->
        </div>

    </div>
</template>

<script>
export default {
    name: 'CabeceraComponent',
    props: {
        msg: String

    },
    data: () => ({
        active: 'guide'
    }),
}
</script>