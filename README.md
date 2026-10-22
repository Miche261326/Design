<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi primera página web</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f3f0ff;
      color: #292344;
      text-align: center;
    }

    header {
      background: #6546d7;
      color: white;
      padding: 45px 20px;
    }

    main {
      max-width: 650px;
      margin: 40px auto;
      padding: 20px;
    }

    button {
      background: #6546d7;
      color: white;
      border: none;
      border-radius: 10px;
      padding: 14px 22px;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background: #4830a5;
    }

    footer {
      padding: 25px;
      color: #655d7d;
    }
  </style>
</head>

<body>
  <header>
    <h1>¡Bienvenido a mi página!</h1>
    <p>Mi primer proyecto creado con programación</p>
  </header>

  <main>
    <h2>Sobre nosotros</h2>
    <p>Esta es mi primera página web.
       Aquí puedo mostrar mis ideas, servicios o productos.</p>

    <button onclick="saludar()">
      Haz clic aquí
    </button>

    <p id="mensaje"></p>
  </main>

  <footer>
    Mi página web · 2026
  </footer>

  <script>
    function saludar() {
      document.getElementById("mensaje").textContent =
        "¡Gracias por visitar mi página!";
    }
  </script>
</body>
</html>
