<template>
  <div class="about">
    <section class="sobre">
      <h2>Empresa xxx</h2>
    </section>
  <div class="row" id="row">
    <div class="col-sm imagem-sobre">
      <img src="../assets/img/semfundo.png" alt="">
    </div>
    <div class="col-sm texto-sobre">
      <h1>empresa xxx</h1>
      <hr class="linha">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
        incididunt ut labore et dolore magna aliqua. Interdum velit laoreet id donec
        ultrices tincidunt arcu non sodales. Euismod nisi porta lorem mollis aliquam 
        ut porttitor leo. Lacus sed turpis tincidunt id aliquet risus feugiat in. Purus 
        sit amet volutpat consequat mauris nunc congue nisi vitae.
      </p>
      <p> 
        Sed nisi lacus sed
        viverra tellus. Bibendum ut tristique et egestas. Sapien pellentesque habitant 
        morbi tristique senectus et netus et. Eu tincidunt tortor aliquam nulla facilisi 
        cras fermentum odio eu. Adipiscing diam donec adipiscing tristique risus. Leo integer 
        malesuada nunc vel risus commodo viverra maecenas accumsan. Ultricies integer quis 
        auctor elit sed vulputate. Fermentum leo vel orci porta non pulvinar neque laoreet 
        suspendisse. 
      </p>
      <p>
        Donec enim diam vulputate ut pharetra sit amet. Cursus euismod quis viverra 
        nibh cras pulvinar mattis nunc sed. Lacus suspendisse faucibus interdum posuere lorem 
        ipsum dolor sit amet. Purus semper eget duis at tellus at. Scelerisque fermentum dui 
        faucibus in ornare quam. Velit sed ullamcorper morbi tincidunt ornare massa. Ac felis 
        donec et odio pellentesque diam.
      </p>
    </div>
  </div>
  <div class="icon">
    <h3>Siga nossas redes socias</h3>
    <hr>
    <div class="icon-social">
      <a href="#"><img src="../assets/img/face1.png" alt=""></a>
      <a href="#"><img class="whats-icon" src="../assets/img/whats1.png" alt=""></a>
      <a href="#"><img src="../assets/img/youtube1.png" alt=""></a>
      <a href="#"><img src="../assets/img/insta1.png" alt=""></a>
    </div>
  </div>
  </div>
</template>
<style>
    .about{
      overflow: hidden;
    }
    .sobre{
      background-image: url('../assets/img/bg.jpg');
      background-repeat: no-repeat;
      background-size: cover;
      height: 400px;
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-items: center;
      text-align: center;
      justify-content: center; 
    }
    .sobre h2{
      font-size: 3.3rem;
      color: #fff;
      text-transform: uppercase;
    }
    #row{
      background-image: url('../assets/img/textura1.png');
      background-repeat: no-repeat;
      background-size: cover;
      height: 100%;
    }
    .imagem-sobre{
      margin-top: 50px;
      height: 100%;
      margin-left: 0;
      margin: 0;
      padding-left: 0;
      width: 100%;
    }
    .texto-sobre h1{
      text-transform: uppercase;
      color: #fff;
      margin: 0 15px;
      text-align: center;
      margin-bottom: 20px;

    }
    .texto-sobre{
      margin-top: 50px;
      text-align: justify;
      margin-right: 30px;
      margin-left: 30px;
      color: #fff;
      opacity: 500%;
    }
    .texto-sobre hr{
      background-color:#fff;
      width: 50%;
      margin-bottom: 20px;
    }
    .icon{
      display: flex;
      align-items: center;
      justify-items: center;
      flex-direction: column;
     /* justify-content: center;*/
      height: 350px;
      background-image: url('../assets/img/texturabranca.png');
      background-repeat: no-repeat;
      background-size: cover;
    }
    .icon h3{
      margin-top: 50px;
      font-size: 2.5rem;
      text-transform: uppercase;
    }
    .icon hr{
      background-color: rgb(7, 22, 22);
      
    }
    .icon-social{
      display: flex;
    }
    .icon-social img{
      height: 70px;
      width: 70px;
      margin: 30px
    }
    .whats-icon{
      height: 150px;
      width: 100px;
    }
    /*mobile*/
    
   
</style>
