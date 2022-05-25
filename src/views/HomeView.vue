<template>
  <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
    </div>
    <div class="carrosel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="../assets/carrossel.jpg"
            width="100px"
            height="500px"
            class="d-block w-100 img-carrossel"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Adotar não ajuda só os animais...</h5>
          </div>
        </div>
        <div class="carousel-item">
          <img
            src="../assets/carrossel1.png"
            class="d-block w-100 img-carrossel"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>Ajuda as ruas a não ficarem lotadas...</h5>
          </div>
        </div>
        <div class="carousel-item">
          <img
            src="../assets/carrossel2.jpeg"
            class="d-block w-100 img-carrossel"
            alt="..."
          />
          <div class="carousel-caption d-none d-md-block">
            <h5>E ajuda você a ficar mais feliz!</h5>
          </div>
        </div>
      </div>

      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">próximo</span>
      </button>
    </div>
    <div class="row">
    <div class="col-lg-15 div-home">
        <img src="../assets/racao.jpg" id="oi" class="rounded-circle img-home"  alt="gato">
        <title>Placeholder</title>
      <h2 class="fw-normal">Ração</h2>
      <p>
        Nós donos dos animais temos que tomar cuidado ao escolher a ração ideal 
        para o nosso pet, pois ela influencia na sua saúde e físico deles...
      </p>
      <p><a class="btn btn-secondary botao-meu" href="#">Ler mais</a></p>
    </div>
    <div class="col-lg-15 div-home">
        <img src="../assets/brinquedo.jpg" id="oi" class="rounded-circle img-home"  alt="gato">
        <title>Placeholder</title>
      <h2 class="fw-normal">Brinquedos</h2>
      <p>
        Os cães e gatos gostam muito de ter os seus próprios brinquedos, 
        então é bom eles terem em casa, pois estimula a diversão deles
      </p>
      <p><a class="btn btn-secondary botao-meu" href="#">Ler mais</a></p>
    </div>
    <div class="col-lg-15 div-home">
        <img src="../assets/agua.jpg" id="oi" class="rounded-circle img-home"  alt="gato">
        <title>Placeholder</title>
      <h2 class="fw-normal">Água</h2>
      <p>
        É obrigatório termos um pote com água perto da cama ou casinha do nosso pet,
        pois sem ela ele poderá passar mal, ou até ocorrer outros imprevistos
      </p>
      <p><a class="btn btn-secondary botao-meu" href="#">Ler mais</a></p>
    </div>
  </div>
  </div>

  <link href="../assets/dist/css/bootstrap.min.css" rel="stylesheet" />

 
  
</template>
