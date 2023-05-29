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
</html/
  
const dataElement = document.getElementById('data');

const data = localStorage.getItem('data');
if (data) {
  dataElement.textContent += data;
} else {
  dataElement.textContent += 'No hay datos almacenados.';
}
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 20px;
}

h1 {
  color: #333;
}

  
  // Manipulación del documento manipulado.html
document.addEventListener('DOMContentLoaded', function() {
  var messageElement = document.getElementById('message');
  messageElement.textContent = 'Texto modificado por JavaScript';
});

// Persistencia de datos mediante Local Storage
var data = {
  name: 'John',
  age: 25
};
localStorage.setItem('userData', JSON.stringify(data));

// Recuperación de datos almacenados en Local Storage
var userData = JSON.parse(localStorage.getItem('userData'));
console.log(userData);

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


