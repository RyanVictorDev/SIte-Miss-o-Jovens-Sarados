<template>
    <nav>
        <div class="logo">
            <img src="../assets/tauRosa.png" alt="Tau Rosa">
            <p>Jovens Sarados</p>
        </div>

        <div class="links">
            <router-link to="/">Home</router-link> |
            <router-link to="/eventos">Eventos</router-link>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'NavbarComponent',

}
</script>

<style scoped>
    nav{
        display: flex;
        background-color: #102542;
        justify-content: space-between;
        padding: 10px;
        padding-left: 3%;
        padding-right: 3%;
    }

    .logo{
        display: flex;
        width: 25%;
    }

    img{
        padding-right: 2%;
    }

    p{
        font-family: sans-serif;
        margin-top: auto;
        margin-bottom: auto;
        color: gainsboro;
    }

    .links{
        margin-top: auto;
        margin-bottom: auto;
    }
</style>