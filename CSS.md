* {
    margin: 0;
    padding:0;
}
 
/* para garantir que estes elementos ocuparão toda a tela */
body, html {
    width: 100%;
    height: 99%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/arts27.jpg") no-repeat fixed;
	background-size: 110% 110%;
}

/* slider do body */

	#slide{
	position: absolute;	
	width: 100%;
    height: 100%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/arts29.jpg") no-repeat fixed;
	background-size: 100% 120%;
	display: none;
}
#slide2{
	position: absolute;	
	width: 100%;
    height: 100%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/arts22.jpg") no-repeat fixed;
	background-size: 130% 130%;
	display: none;
}
#slide3{
	position: absolute;
	width: 100%;
    height: 100%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/arts20.jpg") no-repeat fixed;
	background-size: 100% 100%;
	display: none;
}
#slide4{
	position: absolute;
	width: 100%;
    height: 100%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/arts17.jpg") no-repeat fixed;
	background-size: 100% 100%;
	display: none;
}
#slide5{
	position: absolute;
	width: 100%;
    height: 100%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/arts19.jpg") no-repeat fixed;
	background-size: 100% 100%;
	display: none;
}
#slide6{
	position: absolute;
	width: 100%;
    height: 100%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/arts13.jpg") no-repeat fixed;
	background-size: 100% 100%;
	display: none;
}
#slide7{
	position: absolute;
	width: 100%;
    height: 100%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/arts9.jpg") no-repeat fixed;
	background-size: 100% 100%;
	display: none;
}
#slide8{
	position: absolute;
	width: 100%;
    height: 100%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/arts22.jpg") no-repeat fixed;
	background-size: 100% 100%;
	display: none;
}
#slide9{
	position: absolute;
	width: 100%;
    height: 100%;
    font-family: Comic Sans MS, Tahoma, sans-serif;
	background:url("../Images/destak.jpg") no-repeat fixed;
	background-size: 100% 100%;
	display: none;
}



 
#fundo-externo {
    overflow: hidden; /* para que não tenha rolagem se a imagem de fundo for maior que a tela */
    width: 100%;
    height: 100%;
    position: relative; /* criamos um contexto para posicionamento */
	
}
 
#fundo {
    position: fixed; /* posição fixa para que a possível rolagem da tela não revele espaços em branco */
    width: 100%;
    height: 100%;
}
 
#fundo img {
    width: 100%; /* com isso imagem ocupará toda a largura da tela. Se colocarmos height: 100% também, a imagem irá distorcer */
    position: absolute;
}
 
#site {
	
    position: absolute;
    top: 40px;
    left: 50%;	
    width: 1343px;
	height:  565px;
    padding: 20px;
    margin-left: -700px; /* por causa do posicionamento absoluto temos que usar margem negativa para centralizar o site */
	background: rgba(0,0,0,0);
	
	background-size: 100% 100%;
	
	
	
	
}

	/* Entrar no Tk Arts */
	p{ 
			
	font-size: 40px;
	color: rgba(255,255,255,0.7);
	margin-top: 130px;
	position: absolute;
	font-weight: bold;
	text-shadow: 3px 10px 10px rgba(0,0,0, 0.3); 
	font-style: italic;
	z-index: 20;
	left: 15%;
	
	}
	
	/* Texto que aparece no slider*/
p#p1{
    font-size: 40px;
	color: rgba(0,0,0,1);
	margin-top: 210px;
	position: absolute;
	font-weight: bold;
	text-shadow: 1px 4px 10px rgba(100,100,100,0.3); 
	font-style: italic;
	z-index: 20;
	left: 30%;
}
p#p2 {
    font-size: 40px;
	color: rgba(0,0,0,1);
	left: 7%;
	margin-top: 210px;
	position: absolute;
	font-weight: bold;
	text-shadow: 1px 4px 10px rgba(100,100,100,0.3); 
	font-style: italic;
	z-index: 20;
}
p#p3 {
    font-size: 40px;
	color: rgba(0,0,0,1);
	left: 25%;
	margin-top: 210px;
	position: absolute;
	font-weight: bold;
	text-shadow: 1px 4px 10px rgba(100,100,100,0.3); 
	font-style: italic;
	z-index: 20;
}
p#p4 {
    font-size: 40px;
	color: rgba(0,0,0,1);
	left: 20%;
	margin-top: 210px;
	position: absolute;
	font-weight: bold;
	text-shadow: 1px 4px 10px rgba(100,100,100,0.3); 
	font-style: italic;
	z-index: 20;
}
p#p5 {
    font-size: 40px;
	color: rgba(0,0,0,1);
	left: 25%;
	margin-top: 210px;
	position: absolute;
	font-weight: bold;
	text-shadow: 1px 4px 10px rgba(100,100,100,0.3); 
	font-style: italic;
	z-index: 20;
}	
	/*mascara do texto (slide)*/
	#divmeio{
		
		height: 500px;
		width: 1383px;
		position: absolute;
		background: rgba(0,0,0,0.6);
		margin-top: 32px;
		margin-left: -20px;
		box-shadow : 10px 10px 10px rgba(0,0,0,0.5);
		
	}
	#login{ 
		
		height: 25px;
		width: 100px;
		border: 1px solid white;
		position: absolute;
		left: 40%;
		margin-top: 210px;
		z-index: 20;
		background: ;
		padding: 20px;
		text-align: center;
	}
	#login a{ text-decoration: none; color:white ;}
	#login:hover{ border-color: #5D62FF;}
	
	#cadastrar{ 
		
		height: 25px;
		width: 100px;
		border: 1px solid white;
		position: absolute;
		left: 55%;
		margin-top: 210px;
		z-index: 20;
		text-align: center;
		padding: 20px;
		color: rgba(255,255,255,1);
	}
	 
	 


.saibamais{
		
		position: relative;
		float: right;
		color: black;
		right: 20px;
		top: 5px;
		text-shadow: 1px 1px 1px rgba(255, 255, 255, 0.7); 
		z-index: 10;
		
	
}
.saibamais a{ color: black; text-decoration:none;}

.saibamais:hover{ 
		

		border: solid black 3px;
		border-top: 1px;
		border-right: 1px;
		border-left: 1px;
		
}
	
.cadastrar{
	
	
	position: absolute;
	left: 80.8%;
	top: 5px;
	text-shadow: 1px 1px 1px rgba(255, 255, 255, 0.4); 
	
	z-index: 100;
}
.cadastrar a{ color: rgba(255, 255, 255, 1); text-decoration:none;}

	#borda1{
		
		
		height: 3px;
		width: 0px;
		position: absolute;
		background: url("../Images/jiji9.jpg") fixed no-repeat;
		margin-left: 1098px;
		margin-top: -27px;
		
	}
	#borda2{
		
		
		height: 0px;
		width: 3px;
		position: absolute;
		background: url("../Images/jiji2.jpg");
		margin-left: 1089px;
		margin-top: -54px;
	}
	#borda3{
		
		margin-left: 1180px;
		margin-top: -55px;
		height: 0px;
		width: 3px;
		position: absolute;
		background: url("../Images/jiji.jpg");
		
	}
#top{
	
	position: absolute;
    top: 0px;
    width: 99.99%;
	height:  42px;
	background:rgba(0,0,0,1);
	box-shadow: 5px 5px  10px rgba(0,0,0,0.5);
	min-height: 3%;
	
}

#copyrigth{
	
	
	position: absolute;
    bottom:0 ;
    left: 0;
    width: 99.89%;
	height:  25px; 
	background:rgba(0,0,0,1);
	z-index: 0;
	text-align: center;
	font-size:13px;
	padding-top: 10px;
	text-shadow: 1px 1px 1px rgba(255, 255, 255, 0.3);
	padding-left: 2px;
	color: rgba(255,255,255,0.1);
	z-index: 0;
	min-height: 3%;
}

#copyrigth a{ text-decoration: none; color: rgba(255,255,255,1);}
#copyrigth a:hover{
	
	color: rgba( 255,255,255,0.5);
	
}
		
		/*trocar icone por estar aparecendo parte branca*/

.imgrodape1{
		
		height: 22px;
		width: 22px;
		background-color: rgba(255,255,255,0.7);
		position: absolute;
		margin-left: 77%;

		margin-top: -25px;
		border-radius: 100%;
		box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.4);
		z-index: 100;
		
		-webkit-animation: 5s linear infinite delay 1s;
	}
	.imgrodape2 {
		
		height: 22px;
		width: 22px;
		background-color: rgba(255,255,255,0.7);
		position: absolute;
		margin-left: 79%;
		margin-top: -25px;
		border-radius: 100%;
		box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.4);
		z-index: 100;
		
		-webkit-animation: 5s linear infinite delay 1.2s ;
	}
	.imgrodape3 {
		
		height: 22px;
		width: 22px;
		background-color: rgba(255,255,255,0.7);
		position: absolute;
		margin-left: 81%;
		margin-top: -25px;
		border-radius: 30px;
		box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.4);
		z-index: 100;
		
		-webkit-animation: 5s linear infinite delay 1.4s ;
	}
	.imgrodape4 {
		
		height: 22px;
		width: 22px;
		background-color: rgba(255,255,255,0.7);
		position: absolute;
		border-radius: 30px;
		margin-left: 83%;
		margin-top: -25px;
		box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.4);
		z-index: 100;
		
		-webkit-animation: 5s linear infinite delay 1.8s;
	}
	
	.imgrodape1:hover{ position: absolute ;background: #29D2F1; z-index: 1;} 
	.imgrodape2:hover{ background: #2B72FF;} 
	.imgrodape3:hover{ background: #6A3933;}  	
	.imgrodape4:hover{ background: #FCFF4B;}	
	
	
	.login {
		
		position: absolute;
		height: 30px;
		width: 250px;
		border: 1px solid ;
		border-color: rgba(0,0,0,0.3);
		background: white;
		position: relative;
		margin-left: 130px;
		margin-top: 270px;
		border-radius: 8px 0px 8px;
		
	
	}
	.login:focus{
		
		border-color: lightblue;
	}
	
	.senha {
		
		height: 30px;
		width: 250px;
		border: 1px solid;
		position: absolute;
		outline: none;
		background: white;
		margin-left: 130px;
		margin-top: 230px;
		border-color: rgba(0,0,0,0.3);
		border-radius: 8px 0px 8px;
	}
	::-webkit-input-placeholder{
    
	color: black;
	opacity: 0.7;
	position: absolute;
	padding: 6px;
	font-family: "Comic Sans MS";
	background: url(../Images/jiji.jpg) no-repeat;
	background-size: 100% 10%;
	border-radius: 2px;
	}

	.senha:focus{
		
		border-color: lightblue;
	}
	.entrar{
		
		
		width: 250px;
		height: 50px;
		background: rgba(0,0,0,0.5);
		box-shadow: 1px 4px 20px rgba(0, 0, 0, 0.5);
		color: white;
		position: absolute;
		margin-top:370px;
		font-family: "Comic Sans MS";
		left: 29%;
		border: 0;
	}
	
	.entrar a{
		
		text-decoration: none; color: white;
	}
	.entrar:hover{
		
		background:rgba(0,0,0,1);	
		
	}
	/* container do entrar no Tk arts */
	#container{
		
		height: 600px;
		width: 450px;
		/*border: solid black 1px; Saber onde está o container*/
		position: relative;
		margin-left: 800px;
		margin-top: -40px;
	}
	.manter{
		
		position: absolute;
		margin-top: 3px;
		margin-left: -20px;
		
		
	}
	#lembrar-me{
		
		position: absolute;
		height: 30px;
		width: 200px;
		color: rgba(255,255,255,1);
		/*border: solid black 1px; Saber onde está o container*/	
		margin-top: 20px;
		margin-top: 20px;
		margin-left: 87px;
		text-align: center;
		font-size: 13px;
		
	}
	#esqueceu-senha{
		
		position: absolute;
		height: 30px;
		width: 200px;
		color: rgba("255, 255, 255,1");
		/*border: solid black 1px; Saber onde está o container*/
		margin-top: 130px;
		margin-left: 160px;
		text-align: center;
		font-size: 13px;
		color: rgba(255,255,255,1);
	}
	#esqueceu-senha a{ text-decoration: none; color : blue;}
	
	#criar-conta{
		
		position: absolute;
		height: 30px;
		width: 200px;
		color: black;
		/*border: solid black 1px; Saber onde está o container*/
		margin-top: 160px;
		margin-left: 160px;
		font-size: 13px;
		text-align: center;
		color: rgba(255,255,255,1);
		
	}
		#criar-conta a{ text-decoration: none; color : blue;}
		
		
	#ponto#ponto{
		
		height: 10px;
		width: 10px;
		background: rgba(255,255,255,1);
		position: absolute;
		margin-top: 480px;
		margin-left: 350px;
	}
	
	#ponto2{
		
		height: 10px;
		width: 10px;
		background: rgba(255,255,255,1);
		position: absolute;
		margin-top: 480px;
		margin-left: 400px;
	}
	
	#ponto3{
		
		height: 10px;
		width: 10px;
		background: rgba(255,255,255,1);
		position: absolute;
		margin-top: 480px;
		margin-left: 450px;
	}
	#ponto4{
		
		height: 10px;
		width: 10px;
		background: rgba(255,255,255,1);
		position: absolute;
		margin-top: 480px;
		margin-left: 500px;
	}	
	#ponto5{
		
		height: 10px;
		width: 10px;
		background: rgba(255,255,255,1);
		position: absolute;
		margin-top: 480px;
		margin-left: 550px;
	}	
	/*  fechar slider */
	
	#fechar {
		
		height: 25px;
		width:30px;
		margin-top: 2px;
		position: absolute;
		left: 95%;
		text-shadow: 1px 1px 1px rgba(255, 255, 255, 0.4);
		text-align: center;
		padding-top: 2px;
		font-family: "Comic Sans MS";
		opacity: 0.5;

		}
	#fechar a{ text-decoration: none; color: rgba(255,255,255,1);}	
	#fechar:hover{ text-shadow: 1px 1px 1px rgba(255, 0, 0, 0.4);}
	
	/*  Reabrir slider*/
	#fechar2{
		
		height: 25px;
		width:30px;
		position: absolute;
		left: 5%;
		text-shadow: 1px 1px 1px rgba(255, 255, 255, 0.3);
		text-align: center;
		margin-top: -20px;
		left: 20%;
		font-family: "Comic Sans MS";	
		display: none;
		color: rgba(255,255,255,0.5);
	
		}
	#fechar2 a{ text-decoration: none; color: rgba(255,255,255,0.5);}	
	#fechar2 a:hover{ color: rgba(255,255,255,1);}	
	
	
