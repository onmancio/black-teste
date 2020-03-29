# black-teste
HTML
<!DOCTYPE>
<html>
<head lag="pt-br">
	<link rel="stylesheet" type="text/css" href="style2.css">
	<meta charset="utf-8">
	<title> Meu perfil </title>
</head>

	<body>
		<header class="container">
			<div id="navegador" >
				
				<tr> <a href="#logomarca"><p>Início</p></a> 
				<a href="#div_segunda"><p>Sobre mim</p></a> 
				<a href="#div_terceira"><p>Hobbies</p></a>  </tr>
			</div>

		</header>
			<section class="container">
				<div id="logomarca">
					 <img class="foto-osman" src="facepage.jpeg" height="150px"> <p>Osman Mancio 	</p> 
				</div>					

			
				<div id="div_primeira"> 
					<div> <p> Olá, me chamo Osman Nascimento Mancio, muito conhecido como Osmancio. Atualmente, estou cursando Bacharelado de Ciência e Tecnologias na Universidade Federal do Rio Grande do Norte (UFRN) e tenho um grande interesse em áreas de tecnologia e ciência, como também, aberto para aprender mais sobre progamação e design.  </div>
					<hr>					
					<div> <strong> "A mente que se abre a uma nova idéia jamais retornará ao seu tamanho original" - Albert Einstein </strong></p> </div> 
					<hr>
				</div>
				
				<div id="div_segunda">
					<h2>SOBRE MIM</h2> <p>Recém chegado do interior do Rio Grande do Norte, viví toda minha infância e adolescencia no município de Carnaubais, onde me tornei o ser humano que sou hoje, graças aos meus pais. Desde pequeno levava jeito para empilhar com bloquinhos de Lego, percebía tudo quando está ao meu alcance posso construí-las e  modificá-las quando preciso, levei essa interrelação para toda a minha vida quanto Ser sociável. No Ensino Médio, nas viagens de amostra de profissões na UFRN, ficava adimirado pela grandiosidade e complexidade da instituição (que eu não sonhava que existía), e dizía: "Vou estudar aí!", até que atualmente consegui a minha vaga tão desejada na Universidade, cursando Ciência e Tecnologias. </p> 
				</div>
				<div id="div_terceira">
 
					<h2> HOBBIES </h2>
					<p> Desde interações neuroquímicas do corpo até a comunicação social com a natureza:  </p>
					<p> (Passe o mouse) </p>
					<table>
						<tr> 
							<th> <img src="tests.png" height="70px" class="circulo" title="Neurociência e Psicologia."> </th>
						 
							<th> <img src="cristo.png" height="70px" class="circulo" title="Religião: Cristã."> </th> 
						 
							<th> <img src="sport.png" height="70px" class="circulo" title="Jogar volei ball."> </th> 
						</tr>
						<tr> 
							<th> <img src="beach.png" height="70px" class="circulo" title="A minha onda é a praia, para relaxar."> </th>
						 
							<th> <img src="quimica.png" height="70px" class="circulo" title="Gosto de química."> </th> 
						 
							<th> <img src="fastfood.png" height="70px" class="circulo" title="Adoro aquele sanduba."> </th> 
						</tr>
						<tr> 
							<th> <img src="cactus.png" height="70px" class="circulo" title="Minha terra, meu interior."> </th>
						 
							<th> <img src="games.png" height="70px" class="circulo" title="Tento não gostar, jogos de cartas e dados são comigo mesmo."> </th> 
						 
							<th> <img src="pracima.png" height="70px" class="circulo" title="EJECT foi um oportunidade massa para conhecer coisas novas."> </th> 
						</tr>
					</table>
				</div>
			</section>

		<footer class="container"> 
			<div id="menu">
					<a href="https://www.facebook.com/onmancio" title="Página do Facebook"><img src="facebook.jpg" height="30px"></a>

						<a href="http://www.instagram.com/onmancio/" title="Página do Instagram"> <img src="instagram.jfif" height="30px"></a>

						<a href="http://api.whatsapp.com/send?1=pt_BR&phone=5584996493437" title="Conversa do Whatsapp"> <img src="whats.jfif" height="30px"></a>

			</div>
			<div>
				<h1>
				 ProSEmpre - EJECT © 2020 | Desenvolvido por Osman Mancio  
				</h1>
			</div>

		</footer>

	</body>
CSS

/* Página de apresentação do participante */
/*TAG*/
p{
	color: black;
	text-shadow: 10px 10px 10px #111111
	font-size: 16px;
	font-weight: bolder;
	font-family: helvetica, arial;
	margin:  5px;
}



body{
	padding: 1px;
	font-size:: 62.5%;
	background-color: powderblue;
}

img {
	max-width: 100%;
}

*{
	margin: 0px;
	padding: 0px;
}

header{
	clear: both;
	padding: 1px;
	background-color: white;
	font-family: helvetica;
	font-size: 12px;
	position: fixed;
	background-size: 120px;
	min-inline-size: -webkit-fill-available;
	box-shadow: 0px 6px 28px 0 rgba(0, 0, 0, 0.466); 
	}

footer{
	clear: both;
	background-color: white;
	min-height: 10px;
	text-align: center;
}

h1{
	text-align: center;
	font-size: 18px;
	font-family: helvetica, arial;
}

h2{
	font-family: helvetica;
	text-align: center;
}
/* Onde irá ficar os hobbies em ícones */
table{
	margin: auto;
}

th{
	padding: 0 100px ;
}

strong{
	font-size: 30px;
	font-family: helvetica;
}
/*ID*/
#menu{
	border-radius: 50%;
	margin-top: 40px;
	float: center;
}

#navegador{
	float: left;


}

#navegador a{
	text-decoration: none;
}

#logomarca{
	float: center;
	font-family: helvetica;
	font-size: 50px;
	text-align: center;
	margin: 25px 10px;
	margin-top: 100px;

} 
#logomarca img{
	box-shadow: 1px 1px 30px 1px black;
}

#logomarca p{
	text-shadow: : 1px 1px 30px red;
	font-weight: initial;
}
#div_primeira{
	clear: both;	
	background-color: ;
	width: auto;
	min-height: 100px;
	margin:  5px 0px 5px 0px;
	padding: 0px;
	text-align: center;
	box-shadow: 
}

#div_segunda{
	clear: both;	
	background-color: #6959CD;
	width: auto;
	min-height: 100px;
	margin:  30px 0px 30px 0px;
	padding: 0px;
	text-align: center;
	box-shadow: 0px 0px 28px 0 rgba(0, 0, 0, 5);
}

#div_terceira{
	background-color: #008B8B;
	width: auto;
	min-height: 420px;
	margin:   7px 0px 30px 0px;
	padding: 0px;
	text-align: center;
	font-size: 17px;
	box-shadow: 0px 0px 28px 0 rgba(0, 0, 0, 5);
}

/*CLASS*/
.container{
	width: 1128px;
	margin: 0 auto;
}

.foto-osman{
	border-radius: 50%;
}

/* efeitos */
.circulo{
	margin: 2px;
	overflow: hidden;
	float: left;
	transition: 1s ;
	padding: 20px;
}
.circulo:hover{
	transform: rotateY(360deg);
}
