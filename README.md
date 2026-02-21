[index.html](https://github.com/user-attachments/files/25458931/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Diego Orellana - Asesor Comercial</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70') no-repeat center center/cover;
    color: white;
}

.overlay {
    background: rgba(0,0,0,0.75);
    padding: 40px 20px;
}

.container {
    max-width: 1200px;
    margin: auto;
}

h1 {
    font-size: 48px;
    margin-bottom: 10px;
}

h2 {
    margin-top: 40px;
}

.button {
    display: inline-block;
    padding: 15px 25px;
    background-color: #1f6f54;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
}

.button:hover {
    background-color: #145c44;
}

.flex {
    display: flex;
    flex-wrap: wrap;
    gap: 40px;
    margin-top: 40px;
}

.box {
    flex: 1;
    min-width: 300px;
}

input, select, textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border-radius: 5px;
    border: none;
}

.submit-btn {
    background-color: #1f6f54;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.submit-btn:hover {
    background-color: #145c44;
}

.footer {
    text-align: center;
    margin-top: 50px;
}
</style>

</head>

<body>

<div class="overlay">
<div class="container">

<h1>DIEGO ORELLANA</h1>
<p><strong>Asesor Comercial Automotor</strong></p>
<p>📍 Puerto Madero – Buenos Aires</p>
<p>✔ Atención personalizada en concesionario oficial</p>
<p>📞 11 5517-2220</p>

<a href="#formulario" class="button">RECIBIR COTIZACIÓN PERSONALIZADA</a>

<div class="flex">

<div class="box">
<h2>¿Por qué elegirme?</h2>
<p>Asesoramiento confiable y sin vueltas para que tomes la mejor decisión.</p>

<ul>
<li>✔ Atención directa conmigo, no con call center</li>
<li>✔ Negociación clara y transparente</li>
<li>✔ Opciones de financiación bancaria</li>
<li>✔ Seguimiento hasta que tengas la llave en mano</li>
</ul>

<h2>Marcas 0km</h2>
<p>Honda | Hyundai | Jeep | Jetour | GAC</p>

</div>

<div class="box" id="formulario">

<h2>Prepará tu cotización</h2>

<form action="https://formsubmit.co/brudifel@gmail.com" method="POST">

<input type="hidden" name="_captcha" value="false">

<input type="text" name="Nombre" placeholder="Nombre y apellido" required>

<input type="tel" name="Telefono" placeholder="Teléfono" required>

<select name="Vehiculo_para_entregar">
<option value="">¿Tenés vehículo para entregar?</option>
<option>Si</option>
<option>No</option>
</select>

<select name="Plazo">
<option value="">¿En qué plazo pensás avanzar?</option>
<option>Esta semana</option>
<option>Dentro de 30 días</option>
<option>Estoy averiguando</option>
</select>

<textarea name="Version" placeholder="¿Qué versión estás buscando?"></textarea>

<button type="submit" class="submit-btn">RECIBIR PROPUESTA</button>

</form>

</div>

</div>

<div class="footer">
<p>📍 Puerto Madero – Buenos Aires</p>
<p>📞 +54 9 11 5517-2220</p>
<a href="https://wa.me/5491155172220" class="button">HABLAR DIRECTAMENTE POR WHATSAPP</a>
</div>

</div>
</div>

</body>
</html>
