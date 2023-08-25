
<template>
    <p>banner</p>
    <div class="main-container">
        <h1>Pisos</h1>
        <p>formulário</p>
    </div>
</template>

<script>
import Banner from "../components/Banner.vue"

export default{
    // eslint-disable-next-line vue/multi-word-component-names
    name: "Home",
    components:{
    // eslint-disable-next-line vue/no-unused-components
    Banner
    }
}

</script>

<style scoped>
#main-banner {
    background-image: url('img/fundo.png');
    background-position: 0 -250px;
    background-size: cover;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}



</style>