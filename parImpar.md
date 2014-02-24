<!DOCTYPE HTML>
	<html>
		<head>
			<title>Tema1</title>
		</head>
		<body>
			<script type="text/javascript">

				alert("Pares e impares. clic en aceptar");// alerta inicial


				var numero = prompt("Introduce un número");//declaracion de la variable numero
				 
				var resultado = NumParoImpar(numero);//declaracion de variable resultado
				alert("El número "+numero+" es "+resultado);// alerta de resultado
				 
				function NumParoImpar(numero) 
				{
				  if(numero % 2 == 0) //ciclo de par o impar
				  {
				    return "par";
				  }
				  else
				  {
				    return "impar";
				  }
				}


			</script>
		</body>
	</html>
