<template>
   <div id="app">
    <div class="">
  <b-navbar toggleable="lg" type="dark" variant="dark" class="">
    <div class="container">
    <b-navbar-brand @click="$router.push('/')" style="cursor: pointer"><img class="logo" src="../assets/img/logo.png" alt=""></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="f-right"> 
        <b-nav-item @click="$router.push('/')">Home</b-nav-item>
        <b-nav-item @click="$router.push('about')">Empresa</b-nav-item>
        <b-nav-item @click="$router.push('/servicos')">Serviços</b-nav-item>
        <b-nav-item @click="$router.push('/contatos')">Contatos</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
    </div>
  </b-navbar>
</div>
    <router-view/>
  </div>
</template>

<script>
export default {
    methods:{
      //teste
        logout(){
            console.log("Saiu da aplicação")
        }
    }
}
</script>

<style>
    .logo{
        height: 80px;
        width: 200px;
    }
</style>