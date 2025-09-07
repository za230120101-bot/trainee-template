<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Tarjeta de Presentación Digital</title>
  <style>
    body {
      background: #8ea3d6ff;
      font-family: 'Segoe UI', Arial, Verdana;
      display: flex;
      height: 60vh;
      align-items: center;
      justify-content: center;
    }
    .card {
      background: #fff;
      border-radius: 50px;
      box-shadow: 0 8px 24px rgba(43,88,245,0.15);
      padding: 2rem;
      max-width: 340px;
      text-align: center;
    }
    .exodia {
      background: #fff;
      /*border-radius: 0px;*/
      box-shadow: 0 0px 0px rgba(43,88,245,0.15);
      /*padding: 2rem;*/
      max-width: 300px;
      text-align: left;
      padding-left: 20px
    }
    .card img {
      width: 120px;
      height: 120px;
      border-radius: 30%;
      border: 3px solid #09c3f2ff;
      margin-bottom: 1rem;
      object-fit: cover;
    }
    .card h1 {
      color: #1d276b;
      margin: 0.5rem 0 1rem 0;
      font-size: 1.6rem;
    }
    .interests {
      list-style: none;
      padding: 0;
      margin: 1rem 0;
    }
    .interests li {
      background: #e3eafd;
      color: #2561ce;
      margin: 0.5rem 0;
      border-radius: 8px;
      padding: 0.3rem 1rem;
      display: inline-block;
    }
     .exodia li {
      background: #fff;
      color: #cd3434ff;
      margin: 0.5rem 0;
      border-radius: 8px;
      padding: 0.rem rem;
      display: inline-block;
    }
    .card a {
      text-decoration: none;
      color: #fff;
      background: #2b58f5;
      padding: 0.5rem 1rem;
      border-radius: 8px;
      margin-top: 1rem;
      display: inline-block;
      font-weight: bold;
      transition: background 0.9s;
    }
    .exodia a {
      text-decoration: none;
      color: #fff;
      background: #2b58f5;
      padding: 0.5rem 1rem;
      border-radius: 8px;
      margin-top: 1rem;
      display: inline-block;
      font-weight: bold;
      transition: background 0.1s;
    }
    .card a:hover {
      background: #172c6a;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="1749532200149.jpeg" alt="Avatar">
    <h1>Juan Esteban</h1>
    <p>gusto por la buena musica, cinefilo, aprender cosas que sirven en la vida cotidiana</p>
    <ul class="interests">
      <li>Cocina</li>
      <li>Jugar</li>
      <li>Tocar piano</li>
    </ul>
    <ul class=exodia>
     <ul class="asd">
      <li><a href="https://steamcommunity.com/profiles/76561198848642339/" target="_blank">Steam</a></li>
      <li><a href="https://www.linkedin.com/in/juan-campos-670998182/" target="_blank">Linkedin</a></li>
      <li><a href="https://github.com/labelahundo" target="_blank">Linkedin</a></li>
    </ul></ul>
  </div>
</body>
</html>