<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>

export default {
  name: 'about',
  created(){
    window.document.title = this.$route.meta.title
  }
}
</script>

<style>

</style>
