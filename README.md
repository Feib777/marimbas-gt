<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Marimba Chapina</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f3e7;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #8b0000;
      color: white;
      text-align: center;
      padding: 2rem;
    }
    nav {
      background-color: #d9b382;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #4b2e14;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .imagenes-marimba {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .imagenes-marimba img {
      width: 300px;
      height: auto;
      margin: 10px;
      border: 2px solid #ccc;
    }
    iframe {
      display: block;
      margin: 20px auto;
      width: 80%;
      height: 400px;
    }
    form {
      background-color: #fff;
      padding: 2rem;
      border-radius: 10px;
      max-width: 600px;
      margin: 2rem auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    input, textarea, select {
      width: 100%;
      padding: 0.5rem;
      margin-top: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #8b0000;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Marimba Chapina</h1>
    <p>Promoviendo la marimba guatemalteca por el mundo</p>
  </header>

  <nav>
    <a href="https://es.wikipedia.org/wiki/Marimba" target="_blank">Historia</a>
    <a href="https://www.youtube.com/results?search_query=marimba+guatemalteca" target="_blank">Videos</a>
    <a href="https://www.visitguatemala.com/" target="_blank">Visita Guatemala</a>
  </nav>

  <section>
    <h2>¿Quiénes somos?</h2>
    <p>
      Marimba Chapina es una empresa apasionada por la música tradicional de Guatemala. Nos dedicamos a llevar la magia de la marimba chapina a todos los rincones del planeta, a través de presentaciones, contenidos audiovisuales y colaboraciones internacionales.
    </p>
  </section>

  <section class="imagenes-marimba">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Marimba.jpg" alt="Marimba tradicional](https://aprende.guatemala.com/wp-content/uploads/2017/02/Cu%C3%A1ndo-se-celebra-el-d%C3%ADa-de-la-Marimba-en-Guatemala%C3%A7.jpg)](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRPt-FWe_VVIlI1Z_Kh7N-l2OE5xegBYLOTpw&s">
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Marimba_band.jpg" alt="Banda de marimba">
    <img src="https://upload.wikimedia.org/wikipedia/commons/b/b5/Marimba_player_in_Guatemala.jpg" alt="Músico con marimba">
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Marimba_in_Guatemala.jpg" alt="Marimba en escenario">
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/e6/Marimba_Banda_Guatemala.jpg" alt="Concierto de marimba">
  </section>

  <section>
    <h2>Video destacado</h2>
    <iframe src="https://www.youtube.com/embed/BH_Od4fihbI" title="Video de marimba" allowfullscreen></iframe>
  </section>

  <section>
    <h2>Contáctanos</h2>
    <form action="#" method="post">
      <label for="nombre">Nombre completo:</label>
      <input type="text" id="nombre" name="nombre" required>

      <label for="pais">País:</label>
      <input type="text" id="pais" name="pais" required>

      <label for="email">Correo electrónico:</label>
      <input type="email" id="email" name="email" required>

      <label for="pasatiempos">Pasatiempos:</label>
      <textarea id="pasatiempos" name="pasatiempos" rows="4"></textarea>

      <label for="interes">¿Por qué estás interesado en la marimba?</label>
      <textarea id="interes" name="interes" rows="4"></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer style="text-align: center; background-color: #4b2e14; color: white; padding: 1rem;">
    &copy; 2025 Marimba Chapina | Todos los derechos reservados.
  </footer>

</body>
