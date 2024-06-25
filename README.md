<!DOCTYPE html>
<html>
<head>
	<title>Contenedores con colores</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<div class="container red">Contenedor Rojo <button>Cambiar Color</button></div>
	<div class="container blue">Contenedor Azul <button>Cambiar Color</button></div>
	<div class="container green">Contenedor Verde <button>Cambiar Color</button></div>

	<script>
		// JavaScript code to toggle colors
		const buttons = document.querySelectorAll('button');

		buttons.forEach(button => {
			button.addEventListener('click', () => {
				const container = button.parentNode;
				container.classList.toggle('red');
				container.classList.toggle('blue');
				container.classList.toggle('green');
			});
		});
	</script>
</body>
</html>
.container {
    padding: 20px;
    border: 1px solid #ccc;
    margin: 20px;
  }
  
  .red {
    background-color: red;
  }
  
  .blue {
    background-color: blue;
  }
  
  .green {
    background-color: green;
  }
  
  .red:hover {
    background-color: yellow;
  }
  
  .blue:hover {
    background-color: yellow;
  }
  
  .green:hover {
    background-color: yellow;
  }
