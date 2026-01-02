# -kevin-tour-solution
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
    font-family: Arial, Helvetica, sans-serif;
    background: #f5f5f5;
}
header {
    background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover;
    color: white;
    padding: 80px 20px;
    text-align: center;
}
header h1 {
    font-size: 42px;
    margin-bottom: 10px;
}
header p {
    font-size: 18px;
}
.container {
    padding: 40px 20px;
    max-width: 1100px;
    margin: auto;
}
.section-title {
    text-align: center;
    font-size: 32px;
    margin-bottom: 30px;
    color: #333;
}
.tours {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 20px;
}
.card {
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}
.card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}
.card h3 {
    padding: 15px;
    margin: 0;
}
.card p {
    padding: 0 15px 15px;
    color: #555;
}
.btn {
    display: block;
    margin: 15px;
    padding: 12px;
    background: #25d366;
    color: white;
    text-align: center;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}
.form {
    background: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
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
    padding: 20px;
    margin-top: 40px;
}
.whatsapp-float {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25d366;
    color: white;
    padding: 15px;
    border-radius: 50%;
    font-size: 24px;
    text-decoration: none;
}
</style>
</head>

<body>

<header>
    <h1>Kevin Tour Solution</h1>
    <p>Excursiones y aventuras inolvidables en Punta Cana</p>
</header>

<div class="container">
    <h2 class="section-title">Nuestras Excursiones</h2>

    <div class="tours">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21">
            <h3>Isla Saona</h3>
            <p>Catamarán, piscina natural, almuerzo y bebidas incluidas.</p>
            <a class="btn" href="https://wa.me/18000000000?text=Hola%20quiero%20reservar%20Isla%20Saona%20con%20Kevin%20Tour%20Solution">
                Reservar
            </a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1600373078908-6e8f6b7a9a6b">
            <h3>Buggies</h3>
            <p>Aventura, cuevas, playa y caminos rurales.</p>
            <a class="btn" href="https://wa.me/18000000000?text=Hola%20quiero%20reservar%20Buggies%20con%20Kevin%20Tour%20Solution">
                Reservar
            </a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1518837695005-2083093ee35b">
            <h3>Snorkel & Catamarán</h3>
            <p>Música, snorkel, barra libre y diversión.</p>
            <a class="btn" href="https://wa.me/18000000000?text=Hola%20quiero%20reservar%20Snorkel%20con%20Kevin%20Tour%20Solution">
                Reservar
            </a>
        </div>
    </div>

    <h2 class="section-title">Reserva Ahora</h2>

    <div class="form">
        <input type="text" placeholder="Nombre completo" required>
        <input type="tel" placeholder="Teléfono / WhatsApp" required>
        <select>
            <option>Seleccione excursión</option>
            <option>Isla Saona</option>
            <option>Buggies</option>
            <option>Snorkel & Catamarán</option>
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
