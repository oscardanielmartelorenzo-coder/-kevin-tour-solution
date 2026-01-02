# Kevin Tour Solution 
Público
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kevin Tour Solution | Punta Cana</title>
<style>
body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    background: #f5f5f5;
    color: #333;
}

/* Header */
header {
    background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
}
header h1 {
    font-size: 50px;
    margin-bottom: 10px;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.6);
}
header p {
    font-size: 20px;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.6);
}

/* Container */
.container {
    max-width: 1200px;
    margin: auto;
    padding: 40px 20px;
}

/* Section titles */
.section-title {
    text-align: center;
    font-size: 36px;
    margin-bottom: 30px;
    color: #222;
}

/* Tours grid */
.tours {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
}

/* Cards */
.card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 6px 20px rgba(0,0,0,0.15);
    transition: transform 0.3s;
}
.card:hover {
    transform: translateY(-5px);
}
.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}
.card-content {
    padding: 20px;
}
.card-content h3 {
    margin-top: 0;
    font-size: 24px;
    color: #007bff;
}
.card-content p {
    margin: 10px 0;
}
.card-content .price {
    font-weight: bold;
    color: #25d366;
    font-size: 20px;
}
.card-content .btn {
    display: inline-block;
    margin-top: 10px;
    padding: 12px 20px;
    background: #25d366;
    color: white;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
}
.card-content .btn:hover {
    background: #1ebe5d;
}

/* Form */
.form {
    background: white;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 6px 20px rgba(0,0,0,0.1);
    margin-top: 50px;
}
.form input, .form select, .form textarea {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
    border-radius: 5px;
    border: 1px solid #ccc;
}
.form button {
    background: #007bff;
    color: white;
    padding: 14px;
    width: 100%;
    border: none;
    border-radius: 5px;
    font-size: 16px;
}
footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 25px;
    margin-top: 40px;
}
.whatsapp-float {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25d366;
    color: white;
    padding: 18px;
    border-radius: 50%;
    font-size: 26px;
    text-decoration: none;
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
}
</style>
</head>
<body>

<header>
    <h1>🌴 Kevin Tour Solution 🌴</h1>
    <p>Descubre Punta Cana con nuestras excursiones inolvidables</p>
</header>

<div class="container">
    <h2 class="section-title">Catálogo de Excursiones</h2>

    <div class="tours">
        <!-- Isla Saona -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21">
            <div class="card-content">
                <h3>Isla Saona</h3>
                <p>Disfruta de un día en una de las islas más hermosas del Caribe. Catamarán, piscina natural y almuerzo incluido.</p>
                <p class="price">💵 80 USD por persona</p>
                <a class="btn" href="https://wa.me/18000000000?text=Hola%20quiero%20reservar%20Isla%20Saona%20con%20Kevin%20Tour%20Solution">Reservar</a>
            </div>
        </div>

        <!-- Buggies -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1600373078908-6e8f6b7a9a6b">
            <div class="card-content">
                <h3>Buggies en la Selva</h3>
                <p>Aventura total recorriendo caminos rurales, cuevas y playas vírgenes.</p>
                <p class="price">💵 65 USD por persona</p>
                <a class="btn" href="https://wa.me/18000000000?text=Hola%20quiero%20reservar%20Buggies%20con%20Kevin%20Tour%20Solution">Reservar</a>
            </div>
        </div>

        <!-- Snorkel & Catamarán -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1518837695005-2083093ee35b">
            <div class="card-content">
                <h3>Snorkel & Catamarán</h3>
                <p>Snorkel en arrecifes, barra libre y animación a bordo. ¡Diversión garantizada!</p>
                <p class="price">💵 70 USD por persona</p>
                <a class="btn" href="https://wa.me/18000000000?text=Hola%20quiero%20reservar%20Snorkel%20con%20Kevin%20Tour%20Solution">Reservar</a>
            </div>
        </div>

        <!-- Santo Domingo City Tour -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1551882547-ffb3ba003c7e">
            <div class="card-content">
                <h3>Santo Domingo City Tour</h3>
                <p>Conoce la Zona Colonial y los monumentos históricos de la capital.</p>
                <p class="price">💵 60 USD por persona</p>
                <a class="btn" href="https://wa.me/18000000000?text=Hola%20quiero%20reservar%20City%20Tour%20con%20Kevin%20Tour%20Solution">Reservar</a>
            </div>
        </div>

        <!-- Nado con Delfines -->
        <div class="card">
            <img src="https://images.unsplash.com/photo-1526481280698-1b6aaf5b2d3e">
            <div class="card-content">
                <h3>Nado con Delfines</h3>
                <p>Vive una experiencia única con delfines en un entorno seguro y controlado.</p>
                <p class="price">💵 120 USD por persona</p>
                <a class="btn" href="https://wa.me/18000000000?text=Hola%20quiero%20reservar%20Nado%20con%20Delfines%20con%20Kevin%20Tour%20Solution">Reservar</a>
            </div>
        </div>

    </div>

    <h2 class="section-title">Reserva tu excursión</h2>

    <div class="form">
        <input type="text" placeholder="Nombre completo" required>
        <input type="tel" placeholder="Teléfono / WhatsApp" required>
        <select>
            <option>Seleccione excursión</option>
            <option>Isla Saona</option>
            <option>Buggies en la Selva</option>
            <option>Snorkel & Catamarán</option>
            <option>Santo Domingo City Tour</option>
            <option>Nado con Delfines</option>
        </select>
        <input type="date">
        <textarea placeholder="Mensaje adicional"></textarea>
        <button>Enviar solicitud</button>
    </div>

</div>

<footer>
    <p>📍 Punta Cana, República Dominicana</p>
    <p>© 2026 Kevin Tour Solution</p>
</footer>

<a class="whatsapp-float" href="https://wa.me/18000000000">💬</a>

</body>
</html>
