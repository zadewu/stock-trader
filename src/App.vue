<template>
    <div class="container">
      <app-header></app-header>
      <div class="row">
        <div class="mr-auto">
          <router-view></router-view>
        </div>
      </div>
    </div>
</template>

<script>
  import Header from './components/Header.vue'
  export default {
    components: {
      appHeader: Header
    }
  }
</script>

<style>
  body {
    padding: 20px;
  }

  
</style>
