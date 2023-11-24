# site-espanssivo<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alura Books</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css"
/>
<link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="cabecalho">
        <div class="container">
            <input type="checkbox" id="menu" class="container-botao">
            <label for="menu">
                <span class="cabecalho-menu-hamburguer container-imagem">
                </label>
                <ul class="container-menu">
                    <li class="menu-item-titulo">Categorias</li>
                    <li class="menu-item"><a href="# " class="menu-link">Programação</a></li>
                    <li class="menu-item"><a href="# " class="menu-link">Front-end</Front-end></a></li>
                    <li class="menu-item"><a href="# " class="menu-link">Infraestrutura</a></li>
                    <li class="menu-item"><a href="# " class="menu-link">Business</a></li>
                    <li class="menu-item"><a href="# " class="menu-link">Design & UX</a></li>
                </ul>
            <img class="container-imagem" src="img/Logo.svg" alt="Logo da AluraBooks">
            <h1 class="cabecalho-titulo"><b class="container-titulo-negrito">Alura</b> Books</h1>
        </div>
        <div class="container">
            <a href="#"><img class="container-imagem cabecalho-imagem-transparente" src="img/Favoritos.svg" alt="Meus favoritos"></a>
            <a href="#"><img class="container-imagem" src="img/Sacola.svg" alt="Carrinho de compras"></a>
            <a href="#"><img class="container-imagem" src="img/Usuário.svg" alt="Meu perfil"></a>
        </div>
    </header>
    <section class="banner">
    <h2 class="banner-titulo">Já sabe por onde começar?</h2>
        <p class="banner-texto">Encontre em nossa estante o que precisa para o seu desenvolvimento!</p>
        <input type="search" class="banner-pesquisa" placeholder="Qual será sua próxima leitura?">
</section>
<section class="carrossel">
    <h2 class="carrossel-titulo">últimos lançamentos</h2>
    <!-- Slider main container -->
<div class="swiper">
    <!-- Additional required wrapper -->
    <div class="swiper-pagination"></div>
    <div class="swiper-wrapper">
        <!-- If we need pagination -->
      <!-- Slides -->
      <div class="swiper-slide"><img src="img/Acessibilidade.svg" alt=""></div>
      <div class="swiper-slide"><img src="img/Angular.svg" alt=""></div>
      <div class="swiper-slide"><img src="img/Arquitetura.svg" alt=""></div>
      <div class="swiper-slide"><img src="img/Tuning.svg" alt=""></div>
      <div class="swiper-slide"><img src="img/Liderança.svg" alt=""></div>
      <div class="swiper-slide"><img src="img/MEAN.svg" alt=""></div>
      <div class="swiper-slide"><img src="img/MetricasAgeis.svg" alt=""></div>
      <div class="swiper-slide"><img src="img/ReactNative.svg" alt=""></div>
      ...
    </div>
    <!-- If we need navigation buttons -->
    <div class="swiper-button-prev"></div>
    <div class="swiper-button-next"></div>
    <!-- If we need scrollbar -->
    <div class="swiper-scrollbar"></div>
  </div>
  <div class="card">
    <div class="card-1">
        <div class="card-1-texto">
            <h3 class="card-titulo-1">Talvez você também se interesse por...</h3>
            <h2 class="card-titulo-2">Angulr 11 e Firebase</h2>
            <p class="card-texto">Construindo uma aplicação integrada com a plataforma Google</p>
        </div>
        <img src="img/Card.svg" alt="">
    </div>
    <div class="card-2">
        <ul class="botões">
            <li class="botões-item"><img src="img/Favoritos.svg" alt=""></li>
            <li class="botões-item"><img src="img/Sacola.svg" alt=""></li>
        </ul>
        <a class="botão-link" href="https://www.bombounowa.com/wp-content/uploads/glugluieie-pegadinha-do-malandro.jpg">Saiba mais</a>
    </div>
  </div>
</section>
<script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>
<script>
    const swiper = new Swiper('.swiper', {
        spaceBetween: 10,
        slidesPerView: 3,
        pagination: {
            el: '.swiper-pagination',
            type: 'bullets',
         },
    });
</script>
</body>






</html>