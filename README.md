# Portafolio Asael Rodriguez O&M
http://127.0.0.1:5500/Forma.html#
Trabajo de TSI
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Diseño.css">
</head>
<body>
    <header>
        <nav class="Porfolio seccion-contenido">
            <a href="#" class="Portf-logo">
                <h2 class="Logo-text">💼Mi Portfolio</h2>
            </a>
            <ul class="nav-menu">
                <li class="nav-item"><a href="#" class="nav-link">Inicio</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Sobre mí</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Proyectos</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Contacto</a></li>
           
            </ul>
        </nav>
    </header>

    
    <main>
        <section class="Comptdr-Secn">
            <div class="secn-contnt">
                <div class="comptdr-dtlls">
                    <h2 class="title">Hola, soy un desarrollador</h2>
                    <h3 class="subtitle">Especializado en desarrollo web</h3>
                    <p class="description">Bienvenido a mi portfolio espero te guste lo que ves</p>
                    <div class="buttons">
                        <a href="#" class="btn-pagina">Mi Pagina</a>
                        <a href="#" class="btn-redes">Contáctame</a>
                    </div>
                </div>
            </div>
            <div class="Cmptdr-imagen-wrapper">
                <img src="https://www.pngmart.com/files/1/Laptop-PNG-Transparent-Image.png" alt="Laptop" class="Cmptdr-imagen">
                <h3 class="nombre-desarrollador">Asael Rodriguez</h3>
                <p class="matricula-desarrollador">24-EISN-2-025</p>
            </div>
        </section>
    </main>

    <h1>Hola, Bienvenido</h1>

    <button onclick="miWeb()">Mi web</button>
    
    <script src="script.js"></script>
</body>
</html>

@import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Share Tech Mono", monospace;
}

:root{
    --color1: #b969d8b4;
    --color2: #333;
    --color3: #ff6347;

    --font-weight: 400;
}

ul{
    list-style: none;
}

a{
    text-decoration: none;
}

button{
    cursor: pointer;
    border: none;
    background: var(--color3);
}

img{
    width: 100%;
}

.Cmptdr-imagen {
    transform: scaleX(-1);
    width: 200px;
    max-width: 100%;
    height: auto;
}

.seccion-contenido{
    margin: 0 auto;
    padding: 0 20px;
    max-width: var(--font-weight);
}

header .Porfolio{
    display: flex;
    padding: 20px;
    align-items: center;
    justify-content: space-between;
}
header{
    position: fixed;
    width: 100%;
    z-index: 5;
    background: var(--color1);
}

.Porfolio .Portf-logo .Logo-text{
    color: var(--color2);
    font-size: xx-large;
    font-weight: bold;
}

.Porfolio .nav-menu{
    display: flex;
    gap: 10px;
}

.Porfolio .nav-menu .nav-link{
    padding: 10px 18px;
    color: var(--color2);
    font-size: medium;
    background: var(--color1);
    border-radius: medium;
    transition: 0.3s ease;
}

.Porfolio .nav-menu .nav-link:hover{
    background: gold;
    color: var(--color1);
}

.Comptdr-Secn {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 30px;
    min-height: 100vh;
    background: rgb(55, 26, 88);
    padding: 20px;
}

.Comptdr-Secn .secn-contnt {
    color: whitesmoke;
    max-width: 500px;
}

.Comptdr-Secn .secn-contnt {
    display: flex;
    align-items: center;
    max-height: 100vh;
    color: white;
    justify-content: space-between;
}

.Comptdr-Secn .comptdr-dtlls .title {
    font-size: xx-large;
    color: wheat;
    font-family: "Miniver", sans-serif;
}

.Comptdr-Secn .comptdr-dtlls .subtitle {
   margin-top: 8px;
   max-width: 70%;
   font-size: x-large;
   font-weight: semi-bold;
}

.Comptdr-Secn .comptdr-dtlls .description{
    max-width: 70%;
    margin: 24px 0 40px;
    font-size: medium;
}

.Comptdr-Secn .comptdr-dtlls .buttons{
    display: flex;
    gap: 23px;
}

.Comptdr-Secn .comptdr-dtlls .btn-pagina{
    padding: 10px 26px;
    border: 2px solid transparent;
    color : var(--color2);
    border-radius: 4px;
    background: rgb(198, 166, 52);
    font-weight: 20px;
    transition: 0.3s ease;
}

.Comptdr-Secn .comptdr-dtlls .btn-redes{
    padding: 10px 26px;
    border: 2px solid transparent;
    color : var(--color2);
    border-radius: 4px;
    background: rgb(198, 166, 52);
    font-weight: 20px;
    transition: 0.3s ease;
}

.Comptdr-Secn .comptdr-dtlls .btn-redes:hover{
    color: whitesmoke;
    border-color:whitesmoke;
    background: transparent;
}

.Comptdr-Secn .comptdr-dtlls .btn-pagina:hover{
    color: whitesmoke;
    border-color:whitesmoke;
    background: transparent;
}

.Comptdr-Secn .Cmptdr-imagen-wrapper{
    max-width: 500px;
    margin-right: 30px;
    text-align: center;
}

.nombre-desarrollador {
    color: white;
    margin-top: 15px;
    font-size: 18px;
}

.matricula-desarrollador {
    color: white;
    margin-top: 5px;
    font-size: 14px;
}

@media (max-width: 800px) {
    .Comptdr-Secn {
        flex-direction: column;
    }

    .Comptdr-Secn .Cmptdr-imagen-wrapper {
        max-width: 100%;
    }
}

const button = document.querySelector('.btn-pagina');
button.addEventListener('click', () => {
    window.location.href = 'https://www.google.com';
});

const contactButton = document.querySelector('.btn-redes');
contactButton.addEventListener('click', () => {
    window.location.href = 'https://www.linkedin.com';
});
