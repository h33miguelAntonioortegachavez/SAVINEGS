<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>savinegs</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0000FF; /* azul eléctrico */
      color: white;
      text-align: center;
    }

    header {
      padding: 2rem;
      background-color: #0015FF;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
      text-transform: uppercase;
      letter-spacing: 4px;
    }

    p.descripcion {
      font-size: 1.2rem;
      margin: 1rem auto;
      max-width: 600px;
      background-color: rgba(255, 255, 255, 0.1);
      padding: 1rem;
      border-radius: 10px;
    }

    .botones {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 2rem auto;
      gap: 1rem;
      max-width: 800px;
    }

    .botones button {
      background: linear-gradient(45deg, #00FFFF, #0000FF, #00FFFF);
      border: 2px solid #FFFFFF;
      color: white;
      padding: 1rem 1.5rem;
      border-radius: 50px;
      cursor: pointer;
      font-size: 1rem;
      box-shadow: 0 4px 8px rgba(0,0,0,0.4);
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .botones button:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 12px rgba(0,0,0,0.6);
    }

    footer {
      margin-top: 3rem;
      padding: 1rem;
      font-size: 0.9rem;
      background-color: #0000AA;
    }
  </style>
</head>
<body>
  <header>
    <h1>savinegs</h1>
    <p class="descripcion">
      Pronto savings tendrá una gran variedad de productos para que encuentres el que más se adapte a tu estilo.
    </p>
  </header>
  
  <div class="botones">
    <button>Joyas</button>
    <button>Perfumes</button>
    <button>Ropa</button>
    <button>Uñas Acrílicas</button>
    <button>Eléctricos</button>
    <button>Electrónicos</button>
    <button>Libros</button>
    <button>Mascotas</button>
    <button>Laptops</button>
    <button>Drones</button>
    <button>Celulares</button>
    <button>Calzados</button>
  </div>

  <!--
Creada por Miguel Antonio Ortega Chávez, en Santo Domingo, República Dominicana, iniciada el 20 de enero del año 2025.
Dedico esta página web a mi gato LiLi, lo más lindo. Siempre en vida :LiLi.
-->


  <footer>
    &copy; 2025 savinegs. Todos los derechos reservados.
  </footer>
</body>
</html>
