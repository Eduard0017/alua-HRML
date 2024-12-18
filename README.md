<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="/src/styles/style.css">

    <!-- linkando os arquivos Owl Carousel 2 css -->
    <link rel="stylesheet" href="/src/styles/carousel-owl/owl.carousel.min.css">
    <link rel="stylesheet" href="/src/styles/carousel-owl/owl.theme.default.min.css">

    <script src="https://kit.fontawesome.com/b357c29d3a.js" crossorigin="anonymous"></script>
    
    <title>Netflix</title>
</head>
<body>
    <!-- dados referente ao menu da página -->
    <header>
        <div class="container">            
            <img src="/src/assets/img/logo_netflix.png" alt="Logo Netflix" class="logo">            
            <nav>
                <a href="#">Início</a>
                <a href="#">Séries</a>
                <a href="#">Filmes</a>
                <a href="#">Documentários</a>
            </nav>
        </div>
    </header>

    <!-- dados referente ao filme principal mostrado na página -->
    <main>
        <div class="main-movie">
            <div class="container">
                <h3 class="title-movie">HOUSE OF CARDS</h3>
                <p class="description">Nada pode impedir o político sem escrúpulos Frank Underwood de conquistar Washington. Assista agora a nova temporada de House of Cards que está imperdível.</p>
                <div class="buttons">
                    <button role="button" class="button">
                        <i class="fas fa-play"></i>
                        ASSISTIR AGORA
                    </button>
                    <button role="button" class="button">
                        <i class="fas fa-info-circle"></i>
                        MAIS INFORMAÇÕES
                    </button>
                </div>
            </div>
        </div>        
    </main>

    <div class="carousel-movie">
        <div class="owl-carousel owl-theme">
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini1.jpg" alt="" srcset="">
            </div>
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini2.jpg" alt="" srcset="">
            </div>
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini3.jpg" alt="" srcset="">
            </div>
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini4.jpg" alt="" srcset="">
            </div>
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini5.jpg" alt="" srcset="">
            </div>
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini6.jpg" alt="" srcset="">
            </div>
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini7.jpg" alt="" srcset="">
            </div>
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini8.jpg" alt="" srcset="">
            </div>
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini9.jpg" alt="" srcset="">
            </div>
            <div class="item">
                <img class="box-movie" src="/src/assets/img/mini10.jpg" alt="" srcset="">
            </div>
        </div>        
    </div>

    <!-- linkando os arquivos Owl Carousel 2 js -->
    <script src="/src/scripts/carousel-owl/jquery.min.js"></script>
    <script src="/src/scripts/carousel-owl/owl.carousel.min.js"></script>
    <script src="/src/scripts/carousel-owl/setup.js"></script>

    <footer class="baseboard">
        <p>Clone da Interface da Netflix desenvolvido junto a <a target="_blank" href="https://digitalinnovation.one/" rel="noopener noreferrer">Digital Innovation One</a></p>        
        <p>Repositório <a target="_blank" href="https://github.com/Pleiterson/clone-interface-netflix-html-css-js" rel="noopener noreferrer"> GitHub </a>deste projeto</p><br>
        <p>Desenvolvido por <a target="_blank" href="https://pleiterson.vercel.app/" rel="noopener noreferrer">Pleiterson Amorim</a></p>
    </footer>
</body>
</html>
