<!DOCTYPE html>
<html lang=¨pt-br¨>
	<head>
		<meta charset=¨UTF-8¨>
		<title>Gordão Lanches</title>
		<link rel="stylesheet" href="style.css">

	</head>

	<body>
		<img src="gordao.png">
		<div class="principal">
			<h1>Sobre a lanchonete Gordão lanches</h1>

	 		<p>Localizado no bairro primavera, a lanchonete <strong>Gordão Lanches</strong> traz para o mercado o melhor hamburguer e petiscos. Fundado em 2022, a lanchonete do Gordão é destaque na cidade e conquista clientes dia a dia.</p>

			<p id="missao"><em>Nossa missão é: <strong>‘’Proporcionar o melhor para o seu paladar’’</em></strong></p>
			
			<p>Oferecemos profissionais experientes e capacitados no mundo da culinária gourmet. O padrão de atendimento é excelente e ágil,
			 garantindo satisfação dos nossos clientes.</p>
		</div>


		<div class="Beneficios">
			 <h2>Beneficios</h2>

			 <ul>
			<li class="itens"> *Atendimento aos clientes</li>
			<li class="itens"> *Espaço diferenciado</li>
			<li class="itens"> *Localização</li>
			<li class="itens"> *Profissionais Qualificados</li>
				</ul>
				<img src="beneficio.png" class="imagembeneficio">
			</div>
		</body>
	</html>
	
	
	
	
<!DOCTYPE html>
 <html>
 	<head>
 		<meta charset="utf-8">
 		<title>Produtos - Gordão Lanches</title>
 		<link rel="stylesheet" href="reset.css">
 		<link rel="stylesheet" href="produtos.css">
 	</head>
 	<body>
 		<header>
 			<div class="caixa">
 			<h1><img src="gordao.png"></h1>

 			<nav>
 			<ul>
 					<li><a href="gordao lanches.html">Home</a></li>
 					<li><a href="Produtos.html">Produtos</a></li>
 					<li><a href="https://www.google.com">Contatos</a></li> 
			</ul>
 			</nav>
 		</div>
 			</header>

 			<main>
 				<ul class="produtos">

 				<li>
 					<h2>XGordão</h2>
 					<img src="XGordão.png">
 					<p class="produto-descricao">Maior lanche da cidade, o mais preferido</p>
 					<p class="produto-preco">R$35,00</p>
 				</li>
 				<li>
 					<h2>XLanches</h2>
 					<img src="XLanches.png">
 					<p class="produto-descricao">Lanche saboroso, com muito bacon e maionese</p>
 					<p class="produto-preco">R$23,00</p>
 				</li>
 				<li>
 					<h2>XTalarico</h2>
 					<img src="XTalarico.png">
 					<p class="produto-descricao">Lanche prensado, com muuuita salada</p>
 					<p class="produto-preco">R$15,00</p>
 				</li>
 				</ul>
 			</main>
 		</body>
	 </html>

header {
	background: #BBBBBB;
}

.caixa {
	position: relative;
	width: 940px;
 	margin: 0 auto;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

nav a {
	text-transform: uppercase;
	color: #FE3408:;
	font-weight: bold;
	font-size: 22px;
	text-decoration: none;
}

.produtos {
	margin: 0 auto;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	background: #CCCCCC;
	margin: 0 1.5%;
	padding: 30px 20px;
}
.produtos h2 {
	font-size: 30px;
	font-weight: bold;
}

.produto-descricao {
	font-size: 18px;

}

.produto-preco {
	font-size: 22px;
	font-weight: bold;
}
