<template>
    <div class="wrap-home">
        <Header/>
        <div class="text__custom">Home Page</div>
    </div>
</template>

<script>
import Header from 'Header1/HeaderComponent';
export default {
 components: {
    Header,
 }, 
}
</script>

<style scoped>
    .wrap-home{
        height: 100vh;
        line-height: 100vh;
        text-align: center;
        font-weight: bold;
    }
    .text__custom{
        font-size: 50px;
    }

</style>