# ExamenWebEstaticaFS2023
- index.html
- document1.html
- document2.html
- document3.html
- scripts
  - main.js
- styles
  - main.css
- pages
  - document1.html
  - document2.html
  - document3.html

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles/main.css">
  <title>Documentos HTML</title>
</head>
<body>
  <h1>Documentos HTML</h1>
  <ul>
    <li><a href="pages/document1.html">Documento 1</a></li>
    <li><a href="pages/document2.html">Documento 2</a></li>
    <li><a href="pages/document3.html">Documento 3</a></li>
  </ul>

  <script src="scripts/main.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="../styles/main.css">
  <title>Documento 1</title>
</head>
<body>
  <h1>Documento 1</h1>
  <p id="data">Datos: </p>

  <script src="../scripts/main.js"></script>
</body>
 </html>

document.addEventListener('DOMContentLoaded', function() {
  var messageElement = document.getElementById('message');
  messageElement.textContent = 'Texto modificado por JavaScript';
});

// Persistencia de datos mediante Local Storage
var data = {
  name: 'sara',
  age: 22
};
localStorage.setItem('userData', JSON.stringify(data));
/* Estilos para mobile */
@media (max-width: 600px) {
  h1 {
    font-size: 20px;
  }
}

/* Estilos para desktop */
@media (min-width: 601px) {
  h1 {
    font-size: 30px;
  }
}


