<template>
  <div class="bg-blue-lighten-1 d-flex rounded-pill ma-2 pa-4">
    <span>{{name}}</span>
    <span class="mx-5"> | </span>
    <span>{{amount}}</span>
  </div>
</template>

<script>
  export default {
    props : ['name', 'amount']
  }
</script>

<style>

</style>