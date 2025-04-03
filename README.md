<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
     rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" 
     crossorigin="anonymous">
     <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet"/>
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">

    <link rel="stylesheet" href="style.css">
   
    <title>Profile page</title>
</head>
<body>
  <header>
    <nav class="navbar navbar-expand-md fixed-top navbar-light bg-light">
      <div class="container">
        <a href="#" class="navbar-brand text-black fw-bold"><span class="fw-bold bg-primary bg-gradient p-1 rounded-3 text-light">Port</span>folio</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav"    aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
    
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a href="#" class="nav-link fs-6 text-decoration-underline fw-bold">A propos</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link fs-6 fw-bold text-capitalize">contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
  <main>
    <section class="my-5">
      <div class="container">
        <div class="row justify-content-center align-items-center">
          <div class="col-sm-12 col-md-6 mt-5">
            <h4 class="text-capitalize text-info fw-bold text-center">Front-end developper et/ou designer graphique</h4>
            <p class="text-black fs-6">D’une feuille blanche, il arrive à ce que le site soit fonctionnel, qu’il offre une bonne expérience de navigation pour l’internaute et qu’il intègre des fonctions spécifiques et utiles pour le site.le webdesign demande de la créativité et une connaissance des logiciels de création. </p>
            <p class="text-muted"> Le plus souvent, c’est le développeur web qui va intégrer dans le code du site les éléments de design créés par le webdesigner.</p>
            <div class="d-none d-md-block text-center mt-5"><buttun type="file" class="btn btn-info">Telecharger Cv</buttun></div>
          </div>
          <div class="col-sm-12 col-md-6">
            <img src="imgs/Portfolio.jpg" class="img-fluid mx-md-5 px-md-5" style="height: 500px;" alt="">
          </div>
        </div>
      </div>
    </section>
  </main>
  <section class="about">
    <div class="container mt-5">
      <div class="row justify-content-center align-items-center">
        <h5 class="text-center fs-5 text-uppercase fw-bold text-decoration-underline"><span class="text-info">A</span> propos de moi</h5>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class=" mt-0 p-0 mt-md-5 d-none d-md-block text-center p-md-3 rounded-pill border border-info"style="height: 100px; width: 100px;">
           <span class="fw-bold fs-1" ><i class="bi bi-mortarboard-fill"></i></span>
          </div>
          <div class="text-muted pt-1">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, ad!</p>
          </div>
        </div>
        <div class="col-sm-12 col-md-6">
          <div class="text-center p-1 pt-md-5">
            <h5 class="fw-bold text-uppercase text-decoration-underline">Education</h5>
          </div>
          <ul class="list">
            <li class="list-item">En <span class="fw-bold">2024</span> Certificat de formation sur les suites Adobes: <span class="fw-bold"> Photoshop, Illustrator, Indesign, Adobe Xd</span></li>
            <li class="list-item">
              En <span class="fw-bold"> 2022</span> j'ai obtenu ma licence en Informatique de Gestion à ITECOM
            </li>
            <li class="list-item">
              En <span class="fw-bold"> 2021 </span>j'ai obtenu mon diplome de Technicien superieur en informatique (BTS) au centre d'examen ISI Dakar
            </li>
            <li class="list-item">En <span class="fw-bold"> 2020 </span>Attestation de formation sur le développement personnel à Oratorship Academy</li>
                <li class="list-item">En <span class="fw-bold"> 2018</span> j'ai eu mon baccalauréat en L2 au lycée Chérif Samsidine Aidara de Vélingara</li>
                <li class="list-item">En <span class="fw-bold">2014</span> j'ai obtenu mon BFEM au CEM de Kandia</li>
                <li class="list-item">En <span class="fw-bold"> 2010</span> j'ai obtenu mon CFEE à l'école élementaire de saré Demba Mary</li>
          </ul>
      </div>
    </div>
  </section>
  <section class="services">
    <div class="container m-3 mt-md-5">
      <div class="row justify-content-center align-items-center g-1">
        <h5 class="text-uppercase fw-bold text-center text-decoration-underline pb-1 pb-md-4"><span class="text-info">Mes</span> services</h5>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="card border-0 pt-4 shadow">
            <span class="text-center text-info fw-bold"><i class="bi bi-plug-fill"></i></span>
            <h6 class="card-title text-center">Ui Designer</h6>
            <div class="card-body">
              <img src="imgs/Bagde3.avif" alt="Badge" class="card-img img-fluid" style="height:200px;">
            </div>
          </div>
        </div>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="card border-1 pt-4">
            <span class="text-center text-info fw-bold"><span class="bi bi-speedometer"></span></span>
            <h6 class="card-title text-center">Ux designer</h6>
            <div class="card-body">
              <img src="imgs/Bagde2.jpg" alt="" class="img-fluid card-img" style="height: 200px; width: auto;">
            </div>
          </div>
        </div>
        <div class="col-sm-12 col-md-6 col-lg-4">
          <div class="card border shadow pt-4">
            <span class="text-center text-info fw-bold"><span class="bi bi-qr-code"></span></span>
            <h6 class="card-title text-center">Developpeur</h6>
            <div class="card-body">
              <img src="imgs/Badge4.jpg" alt="" class="img-fluid card-img" style="height: 200px; width: auto;">
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="contact">
    <div class="container m-3">
      <div class="row justify-content-center align-items-center bg-light">
        <h5 class="text-uppercase fw-bold text-decoration-underline text-center mt-3"><span class="text-info">Me</span> Contacter</h5>
        <div class="col-sm-12 col-md-6 col-lg-4 bg-white m-3 rounded-3">
          <form action="formulaire.html">
           <div class="m-2">
            <label for="prenom" class="form-label">Prenom</label>
            <input type="text" name="prenom" id="prenom" class="form-control">
           </div>
           <div class="m-2">
            <label for="nom" class="form-label">Nom</label>
            <input type="text" name="nom" id="nom" class="form-control">
           </div>
           <div class="m-2">
            <label for="e-mail" class="form-label">E-mail</label>
            <input type="email" name="e-mail" id="e-mail" class="form-control">
           </div>
           <button class="btn btn-primary m-2">Envoyer</button>
          </form>
        </div>
      </div>
    </div>
  </section>
  <section class="footer">
    <div class="container m-3 mt-md-5 bg-light">
      <div class="row justify-content-center g-1 align-items-center">
        <div class="col-md-4 text-center">
          <a href="#Contact" class="text-decoration-none text-capitalize text-muted fs-6 fw-bold">contact</a>
          <div class="text-center text-md-start ps-md-4">
            <span class="text-black fs-6 text-center text-md-start"><i class="bi bi-telephone text-info pe-1"></i>78 483 30 30</span>
          </div>
          <div class="text-center text-md-start ps-md-4">
            <span class="text-center text-md-start" ><i class="bi bi-envelope text-info pe-1"></i>boubacartourebalde2@gmail.com</span>
          </div>
          <div class="text-center text-md-start ps-md-4">
            <span class="text-center text-md-start"><i class="bi bi-geo-fill text-info pe-1"></i>Dakar, Pikine, Dalifort</span>
          </div>
        </div>
        <div class=" col-md-4 text-center">
          <a href="#Apropos" class="text-decoration-none text-capitalize text-muted fs-6 fw-bold">A propos</a>
          <h6 class="text-muted">je suis un créateur libre, avec trois(3) metiers: Designer graphique, web designer et développeur web Front-end </h6>
        </div>
        <div class="col-md-4 text-center">
          <a href="#Meservices" class="text-decoration-none text-capitalize text-muted fs-6 fw-bold">Mes services</a>
          <div class="text-center text-md-start p-0 ps-md-4">
            <a href="#" class="fs-6 text-muted text-decoration-none "><i class="bi bi-plug-fill text-info pe-1"></i>Ui Designer</a>
          </div>
          <div class="text-center text-md-start p-0 ps-md-4">
            <a href="#" class="fs-6 text-muted text-decoration-none "><i class="bi bi-speedometer text-info pe-1"></i>Ux Designer</a>
          </div>
          <div class="text-center text-md-start p-0 ps-md-4">
            <a href="#" class="fs-6 text-muted text-decoration-none "><i class="bi bi-qr-code text-info pe-1"></i>Developpeur</a>
          </div>
        </div>
      </div>
    </div>
  </section>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
</body>
</html>
