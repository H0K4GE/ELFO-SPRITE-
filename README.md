# ELFA-SPRITE-
KEYFRAME de uma elfa

<!DOCTYPE html>
	<html lang="pt-br">
		<head>
		<meta charset="utf-8">
		<title>ELFO{SPRITE}</title>

			<style>
				body{background-color: #8640D6;}		

				#animation {
				background-image: url("naruto/img3.png");
				width: 350px;
				height:500px;
				-webkit-animation: ciclo-animacao 2.0s steps(9) infinite;
				animation: ciclo-animacao 2.0s steps(9) infinite;
				}

				@-webkit-keyframes ciclo-animacao {
				from{ background-position: 0px; }
				to { background-position: -464px; }
				}

				@keyframes ciclo-animacao {
				from { background-positon: 0px; }
				to { background-position: -464px;}
				}
			</style>

		</head>
		<body>

			<div id="animation"></div>	

		</body>
	</html>	
