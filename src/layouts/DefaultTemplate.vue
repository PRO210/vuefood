<template>
    <div>
        <ul><li><router-link :to="{name: 'home'}">home</router-link></li></ul>
        <ul><li><router-link :to="{name: 'loja'}">loja</router-link></li></ul>
        <ul><li><router-link :to="{name: 'cart'}">cart</router-link></li></ul>


        <router-view></router-view>
    </div>
</template>
<script>

import 'bootstrap'
import 'bootstrap/dist/css/bootstrap.min.css'

export default {
    
}
</script>

<style scope>
    @import url('../assets/css/vuefood.css');
    @import url('../assets/css/reset.css');
</style>