<template>
    <footer>
        <p>MISSÃO Jovens Sarados</p>
        <p class="fundador">Fundada pelo Pe. Edimilson Lopes</p>
    </footer>
</template>

<script>
    export default{
        name: 'FooterComponent'
    }

</script>

<style scoped>
    footer{
        display: flex;
        flex-direction: column;
        background-color: #102542;
        padding-top: 15px;
        padding-bottom: 15px;
    }

    p{
        text-align: center;
        color: gainsboro;
    }

    .fundador{
        margin-top: 10px;
    }
</style>