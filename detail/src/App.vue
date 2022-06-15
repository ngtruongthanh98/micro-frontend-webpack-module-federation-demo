<template>
    <div class="wrap-detail">
        <Header/>
        <div class="text__custom">Detail Page</div>
    </div>
</template>

<script>
import Header from 'Header/HeaderComponent';
export default {
 components: {
     Header,
 },   
}
</script>

<style scoped>
    .wrap-detail{
        height: 100vh;
        line-height: 100vh;
        text-align: center;
        font-weight: bold;
    }
    .text__custom{
        font-size: 50px;
    }

</style>