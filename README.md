 # https://ViajesFronteraFrontera.com.mx
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logo Agencia de Viajes Frontera Frontera">
        </div>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Destinos</a></li>
                <li><a href="#">Ofertas</a></li>
                <li><a href="#">Servicios</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
        <div class="search-bar">
            <input type="text" placeholder="Buscar vuelos, hoteles, autos...">
            <button>Buscar</button>
        </div>
    </header>
    
    <main>
        <section class="carousel">
            <img src="destino1.jpg" alt="Destino 1">
            <img src="destino2.jpg" alt="Destino 2">
        </section>

        <section class="offers">
            <h2>Ofertas Destacadas</h2>
            <div class="offer">
                <img src="oferta1.jpg" alt="Oferta 1">
                <p>Descuento en vuelos a Cancún</p>
                <button>Reservar ahora</button>
            </div>
            <!-- Más ofertas -->
        </section>

        <section class="popular-destinations">
            <h2>Destinos Populares</h2>
            <div class="destination">
                <img src="destino1.jpg" alt="Destino 1">
                <p>Cancún</p>
            </div>
            <!-- Más destinos -->
        </section>

        <section class="testimonials">
            <h2>Testimonios</h2>
            <p>"Excelente servicio y atención!" - Juan Pérez</p>
            <!-- Más testimonios -->
        </section>
    </main>
    
    <footer>
        <div class="quick-links">
            <a href="#">Inicio</a>
            <a href="#">Destinos</a>
            <a href="#">Ofertas</a>
            <a href="#">Servicios</a>
            <a href="#">Contacto</a>
        </div>
        <div class="social-media">
            <a href="#"><img src="facebook.png" alt="Facebook"></a>
            <a href="#"><img src="twitter.png" alt="Twitter"></a>
        </div>
        <p>&copy; 2024 Agencia de Viajes Frontera Frontera</p>
    </footer>
</body>
</html>
css
Copiar código
/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #007bff;
    color: white;
    display: flex;
    justify-content: space-between;
    padding: 10px 20px;
    align-items: center;
}

header .logo img {
    height: 50px;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
    padding: 0;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

header .search-bar {
    display: flex;
}

header .search-bar input {
    padding: 5px;
    margin-right: 5px;
}

header .search-bar button {
    padding: 5px 10px;
}

.carousel {
    display: flex;
    overflow: hidden;
}

.carousel img {
    width: 100%;
    height: auto;
}

.offers, .popular-destinations, .testimonials {
    padding: 20px;
    text-align: center;
}

.offers .offer, .popular-destinations .destination {
    margin: 10px;
    display: inline-block;
    width: 200px;
}

footer {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 20px;
}

footer .quick-links a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

footer .social-media a img {
    width: 30px;
    margin: 0 10px;
}

