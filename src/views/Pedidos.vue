<template>
  <div class="main-container">
    <h1>Gerenciar pedidos: </h1>
    <Dashboard />
  </div>
</template>

<script>
  import Dashboard from '@/components/Dashboard.vue';
  
  export default {
    name: "Pedidos",
    components: {
      Dashboard,
    }
  }
</script>

<style scoped>
.main-container{
  min-height: calc(100vh - 280px);
}
</style>