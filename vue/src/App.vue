<template>
  <div id="app" class="small-container">
    <custom-header />
    <h1>Jojo's Photography</h1>
  
    <photo-collage />
    <custom-footer currentyear="2019" company="Jojo's Photography"/>
  </div>
</template>

<script>
  import PhotoCollage from '@/components/PhotoCollage.vue'
  import CustomHeader from '@/components/CustomHeader.vue'
  import CustomFooter from '@/components/CustomFooter.vue'

  export default {
    name: 'app',
    components: {
      PhotoCollage,
      CustomHeader,
      CustomFooter
    },
  }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
