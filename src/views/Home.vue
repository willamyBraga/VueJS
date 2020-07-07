<template>
  <div class="home text-center">
    <b-jumbotron class="jumbotron-with-background" header="Empresa XX" lead="Os melhores serviços estão aqui">
        <p>Serviços de qualidade, etc</p>
        <b-button variant="primary" @click="$router.push('/servicos')">Serviços</b-button>
    </b-jumbotron>
    <div class="container conteudo">
      <div class="row card-service">
        <div class="col-12 col-sm-4 pb-2">
                 <div class="card" style="18rem;">
          <img src="../assets/img/banner1.jpg" class="card-img-top" alt="">
          <div class="card-body">
            <h5 class="card-title">
              serviço 1
            </h5>
            <p class="card-text">Breve descrição</p>
             <router-link to="/servico" class="card-link text-white btn btn-primary">Conheça mais</router-link>
          </div>
        </div>
        </div>
        <div class="col-12 col-sm-4 pb-2">
        <div class="card" style="18rem;">
          <img src="../assets/img/banner1.jpg" class="card-img-top" alt="">
          <div class="card-body">
            <h5 class="card-title">
              serviço 2
            </h5>
            <p class="card-text">Breve descrição</p>
           <router-link to="/servico" class="card-link text-white btn btn-primary">Conheça mais</router-link>
          </div>
        </div>
        </div>
         <div class="col-12 col-sm-4 pb-2">
          <div class="card" style="18rem;">
            <img src="../assets/img/banner1.jpg" class="card-img-top" alt="">
            <div class="card-body">
              <h5 class="card-title">
                serviço 3
              </h5>
              <p class="card-text">Breve descrição</p>
              <router-link to="/servico" class="card-link text-white btn btn-primary">Conheça mais</router-link>
            </div>
        </div>
        </div>
      </div>
    </div>

    <!-- Contédo a baixo pode conter links ou algo do tipo -->
    <div class="links-social">
      <div id="links">Link 1</div>
      <div id="links">Link 2</div>
      <div id="links">Link 3</div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'home',
  
}
</script>
<style>
  .jumbotron-with-background {
    background-image: url('../assets/img/bg.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    color: #fffc;
  }
  .conteudo{
    background-image: url('../assets/img/texturabranca.png');
    background-repeat: no-repeat;
    background-size: cover;
  }
  .card-service{
    background-color: #ffff;
  }
  .links-social{
    display: flex;
    justify-content: center;
    background-image: url('../assets/img/textura2.png');
    background-repeat: no-repeat;
    background-size: cover;
    margin: 20px;
    color: #fff;
  }
#links{
    margin: 50px;
    font-size: 50px;
    cursor: pointer;
}

</style>