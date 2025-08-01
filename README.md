# lavih_fiat
Trabalho de recuperação 
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FIAT</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

    <header class="header">
        <div class="menu-left">
            <i class="fas fa-bars"></i>
            <span>MENU</span>
        </div>
        <div class="logo-center">
            <img src="transferir.png" alt="Logo da FIAT" class="fiat-logo">
        </div>
        <div class="user-right">
            <i class="fa fa-user-circle"></i>
            <span> Cadastre-se</span>
        </div>
    </header>

    <main class="hero-section">
        <img src="Fiat-Fastback (10).jpg" alt="Novo Fiat Fastback" class="hero-image">
        <div class="hero-text">
            <h1>Novo Fiat Fastback</h1>
            <h2>Revele a sua melhor versão.</h2>
            <a href="#" class="cta-button">CONHEÇA</a>
        </div>
    </main>

    <section class="destaques">
        <div class="destaque-item maior">
            <img src="fiat-pulse-abarth-2023-espaco-interno.jpg" alt="Abarth">
            <div class="overlay">
                <h2>ABARTH</h2>
                <p>Sinta a emoção do DNA Abarth: um símbolo de esportividade e potência em cada curva.</p>
                <a href="#">SAIBA MAIS ></a>
            </div>
        </div>

        <div class="destaque-item menor">
            <img src="banner-vd-rural-tablet.webp" alt="Plano Fazendeiro">
            <div class="overlay">
                <h2>PLANO FAZENDEIRO</h2>
                <a href="#">SAIBA MAIS ></a>
            </div>
        </div>

        <div class="destaque-item menor">
            <img src="i648987.jpeg" alt="Connect Me">
            <div class="overlay">
                <h2>CONNECT///ME</h2>
                <p>A plataforma de serviços conectados dos veículos Fiat.</p>
                <a href="#">SAIBA MAIS ></a>
            </div>
        </div>
    </section>

</body>
</html>



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
}


.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;
    background-color: #000;
    color: #fff;
}

.header .fiat-logo {
    height: 40px;
}

.menu-left, .user-right {
    display: flex;
    align-items: center;
    gap: 10px;
}

.menu-left span, .user-right span {
    font-size: 14px;
}


.hero-section {
    position: relative;
    text-align: center;
    color: #fff;
    overflow: hidden;
    height: 80vh;
}

.hero-section .hero-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    filter: brightness(0.6);
}

.hero-text {
    position: absolute;
    top: 50%;
    left: 10%;
    transform: translateY(-50%);
    text-align: left;
}

.hero-text h1 {
    font-size: 4em;
    margin-bottom: 10px;
}

.hero-text h2 {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.cta-button {
    background-color: #979a9b;
    color: #fff;
    padding: 15px 30px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}


.destaques {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
}

.destaque-item {
    position: relative;
    width: 100%;
    height: 400px;
    overflow: hidden;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.destaque-item.maior {
    flex: 2 1 100%;
    height: 600px;
}

.destaque-item.menor {
    flex: 1 1 calc(50% - 10px);
}

.destaque-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: rgba(0, 0, 0, 0.7);
    color: #fff;
    padding: 20px;
    text-align: left;
}

.overlay h2 {
    margin-bottom: 10px;
}

.overlay a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}
