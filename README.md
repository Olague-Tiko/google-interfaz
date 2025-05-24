<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Google Simple</title>
  <style>
    body { margin: 0; font-family: sans-serif; text-align: center; background: #fff; }
    header, footer {
      background: #f8f9fa; padding: 10px 20px;
      display: flex; justify-content: space-between; align-items: center;
    }
    nav a { margin: 0 10px; text-decoration: none; color: #555; font-size: 14px; }
    .logo span { font-size: 36px; font-weight: bold; }
    .logo span:nth-child(1) { color: #4285F4; }
    .logo span:nth-child(2) { color: #EA4335; }
    .logo span:nth-child(3) { color: #FBBC05; }
    .logo span:nth-child(4) { color: #4285F4; }
    .logo span:nth-child(5) { color: #34A853; }
    .logo span:nth-child(6) { color: #EA4335; }
    .profile { width: 32px; height: 32px; background: #ccc; border-radius: 50%; }
    main { margin-top: 80px; }
    input[type="text"] {
      width: 400px; padding: 10px; border-radius: 24px;
      border: 1px solid #ccc;
    }
    .buttons { margin-top: 20px; }
    .buttons input {
      margin: 5px; padding: 8px 16px; border: none;
      background: #f8f9fa; cursor: pointer; border-radius: 4px;
    }
    .buttons input:hover { background: #e0e0e0; }
    footer { justify-content: center; gap: 15px; font-size: 13px; flex-wrap: wrap; }
  </style>
</head>
<body>

  <header>
    <nav><a href="#">Gmail</a><a href="#">Imágenes</a></nav>
    <div class="logo">
      <span>G</span><span>o</span><span>o</span><span>g</span><span>l</span><span>e</span>
    </div>
    <div class="profile"></div>
  </header>

  <main>
    <form action="https://www.google.com/search" method="GET">
      <input type="text" name="q" placeholder="Buscar en Google...">
      <div class="buttons">
        <input type="submit" value="Buscar con Google">
        <input type="submit" name="btnI" value="Voy a tener suerte">
      </div>
    </form>
  </main>

  <footer>
    <nav>
      <a href="#">Publicidad</a>
      <a href="#">Negocios</a>
      <a href="#">Privacidad</a>
      <a href="#">Términos</a>
    </nav>
  </footer>

</body>
</html># google-interfaz
Este es mi primer proyecto aprendiendo a usar html y css intentando simular la interfaz o página principal de google
