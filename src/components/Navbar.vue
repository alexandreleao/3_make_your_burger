<template>
   <div id="nav">
   <router-link to="/">
     <img src="" id="logo">
   </router-link>
    <router-link to="/">Home</router-link> |
    <router-link to="/pedido">Pedidos</router-link>
  </div>
</template>

<script>
export default {
    name: "Navbar",
    data(){
        return{

        }
    }
}
</script>

<style scoped>

</style>