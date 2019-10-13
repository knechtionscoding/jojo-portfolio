<template>
    <div id="custom-header">
        <a href="#default" class="logo"><img src="../assets/logo.jpg" width="82" height="86" title="Jojo Logo" alt="Jojo Logo"></a>
        <h1>Jojo's Photography</h1>
        <!-- <div class="header-right">
            <a class="active" href="#home">Home</a>
            <a href="#contact">Contact</a>
            <a href="#about">About</a>
        </div> -->
    </div>
</template>

<script>
  export default {
    name: 'CustomHeader',
  }
</script>

<style scoped>
#custom-header{
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>