<template>
  <div id="app"> 
      <Header />
      <Footer />
  </div>
</template>
<script>
 import Header from './components/Header'
 import Footer from './components/Footer'
export default {
  components:{
    Header,
    Footer
  }
}
</script>
<style>
#app{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
