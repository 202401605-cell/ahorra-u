<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Barrio Chino</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Barrio Chino Online</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menuPrincipal">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="menuPrincipal">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link active" href="#">Inicio</a></li>
          <li class="nav-item"><a class="nav-link" href="#servicios">Servicios</a></li>
          <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <header class="bg-primary text-white text-center py-5">
    <div class="container py-4">
      <h1 class="display-4 fw-bold">Compra al mejor Precio</h1>
      <p class="lead mb-4">El mejor mecado informal de Cochabamba</p>
      <a href="#servicios" class="btn btn-light btn-lg fw-semibold">Ver ofertas</a>
    </div>
  </header>

  <section class="container my-5">
    <div class="row justify-content-center">
      <div class="col-12 col-md-8 col-lg-6">
        <form id="formBusqueda" class="input-group">
          <input type="text" id="inputBusqueda" class="form-control" placeholder="Buscar tecnología o curso..." required>
          <button class="btn btn-primary" type="submit">Buscar</button>
        </form>
      </div>
    </div>
  </section>

  <section id="servicios" class="container mb-5">
    <h2 class="text-center mb-4">Articulos Robados</h2>
    <div class="row g-4" id="contenedorTarjetas" >

      <div class="col-12 col-sm-6 col-lg-3">
        <div class="card producto-card h-100">
            <img src="j7.webp" class="card-img-top" alt="j7">
            <div class="card-body d-flex flex-column">
                <h5 class="card-title">Celular Samsung J7</h5>
                <p class="card-text">Celular robado en la zona sur</p>
                <p class="card-text">6 de Ram</p>
                <p class="card-text">128 de Rom</p>
                <p class="card-text">Pantalla rota</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
        </div>
      </div>
      
      

        <div class="col-12 col-sm-6 col-lg-3">
          <div class="card producto-card h-100">
            <img src="iphone6s.webp" class="card-img-top" alt="iphone 6 s" height="250px">
            <div class="card-body d-flex flex-column">
                <h5 class="card-title">Celular gama Alta Como nuevo Unico dueño</h5>
                <p class="card-text">2000bs precio fijo</p>
                <p class="card-text">Solo WiFi</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
          </div>
        </div>
        

        <div class="col-sm-6 col-lg-3">
          <div class="card producto-card h-100">
            <img src="toyota-corolla.webp" class="card-img-top" alt="Corolla 1993">
            <div class="card-body d-flex flex-column">
                <h5 class="card-title">Toyota Corolla sin placa</h5>
                <p class="card-text">Solo chapare ojito</p>
                <p class="card-text">1500 kilometros como nuevo</p>
                <p class="card-text">5 choques pero como nuevo</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
        </div>
        </div>

        <div class="col-sm-6 col-lg-3">
          <div class="card producto-card h-100">
            <img src="celullar-dedo.jpeg" class="card-img-top" alt="celular con dedo">
            <div class="card-body d-flex flex-column">
                <h5 class="card-title">Celular gama alta de un Jaila</h5>
                <p class="card-text">Se vende ya nomas barato</p>
                <p class="card-text">Se puede restaurar con el dedo</p>
                <p class="card-text">Ya nomas choquitos entrega Av panamericana</p>
                <a href="#" class="btn btn-primary">Comprar</a>
            </div>
        </div>
        </div>

    </div>
  </section>

  <footer id="contacto" class="bg-dark text-white text-center py-4 mt-auto">
    <div class="container">
      <p class="mb-1">&copy; 2026 Barrio Chino ONLINE - xs</p>
      <small class="text-secondary">Desarrollado con HTML5, Bootstrap 5</small>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script src="app.js"></script>
</body>
</html>
