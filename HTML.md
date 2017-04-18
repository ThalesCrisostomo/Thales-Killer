<!DOCTYPE html>
	<head>
	<title> Home  </title>
	<link rel="shortcut icon" href="/Images/favicon.ico">
	<meta name="viewport" content="user-scalable=no">
	<meta charset="UTF-8">
	<link rel="stylesheet" type="text/css" href="CSS/estilopaginainicial.css">
	<link rel="stylesheet" type="text/css" href="CSS/animate.css">
	
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.2/jquery.min.js"></script>
	<script>
	
	
	$(document).ready(function(){
	
		
		
		setTimeout(function(){ 	
			$("body").show(function(){
				$("#slide").delay("slow").fadeIn(3000);	
				$("#slide").fadeTo(5000, 1);
			});
		}, 2000);
		
		
		
		setTimeout(function(){
			$("#site").show(function(){
				$("p#p1").delay("slow").fadeIn(1000);
				$("p#p1").delay("slow").fadeOut(2000);
				$("#ponto").fadeTo(300, 0.3);
			});
		}, 1000);
		
		setTimeout(function(){
			$("#site").show(function(){
				$("p#p2").delay("slow").fadeIn(1000);
				$("p#p2").delay("slow").fadeOut(2000);
				$("#ponto").fadeTo(1000, 1);
				$("#ponto2").fadeTo(1000, 0.3);
			});
		}, 5000);
		
		setTimeout(function(){
			$("#site").show(function(){
				$("p#p3").delay("slow").fadeIn(1000);
				$("p#p3").delay("slow").fadeOut(2000);
				$("#ponto2").fadeTo(1000, 1);
				$("#ponto3").fadeTo(1000, 0.3);
			});		
		}, 9000);
		
		setTimeout(function(){
			$("#site").show(function(){
				$("p#p4").delay("slow").fadeIn(1000);
				$("p#p4").delay("slow").fadeOut(2000);
				$("#ponto3").fadeTo(1000, 1);
				$("#ponto4").fadeTo(1000, 0.3);
			});		
		}, 13000);
		
		setTimeout(function(){
			$("#site").show(function(){
				$("p#p5").delay("slow").fadeIn(1000);
				$("p#p5").delay("slow").fadeOut(2000);
				$("#ponto4").fadeTo(1000, 1);
				$("#ponto5").fadeTo(1000, 0.3);
			});		
		}, 17000);
		
		setTimeout(function(){
			$("#site").show(function(){
				$("#ponto5").fadeTo(1000, 1);
				$("#ponto").delay("slow").fadeOut(2000);
				$("#ponto2").delay("slow").fadeOut(2000);
				$("#ponto3").delay("slow").fadeOut(2000);
				$("#ponto4").delay("slow").fadeOut(2000);
				$("#ponto5").delay("slow").fadeOut(500);
				});		
		}, 19000);
		
		$("#fechar").click(function(){
		 	$("#divmeio").fadeOut(2000);
			$("#ponto").fadeOut(2000);
			$("#ponto2").fadeOut(2000);
			$("#ponto3").fadeOut(2000);
			$("#ponto4").fadeOut(2000);
			$("#ponto5").fadeOut(2000);
		});
		
		$("#fechar").mouseenter(function(){
			$(this).css("opacity","1");
		});
		
		$("#fechar").mouseleave(function(){
			$(this).css("opacity","0.5")
		});

		// chamando o botão de reabrir o slider
		
		$("#fechar").click(function(){
			$("#fechar2").show(1000);
			
			
		});
		$("#fechar2").click(function(){
			$("#fechar").show(1000);
			$("#fechar2").hide(1000);
		});
		
		$("#fechar2").click(function(){
			$("#divmeio").fadeIn(2000);
			$("#ponto").fadeIn(2000);
			$("#ponto2").fadeIn(2000);
			$("#ponto3").fadeIn(2000);
			$("#ponto4").fadeIn(2000);
			$("#ponto5").fadeIn(2000);
		});
		
		
		 $(".cadastrar").mouseenter(function(){
			$("#borda1").animate({width: "75px"}, 300);
		});
		
		$(".cadastrar").mouseleave(function(){
			$("#borda1").animate({width: "0px"}, 300);
		});
		
		$(".cadastrar").mouseenter(function(){
			$("#borda2").animate({height: "30px"}, 300);
		});
		
		$(".cadastrar").mouseleave(function(){
			$("#borda2").animate({height: "0px"}, 300);
		});
		
		$(".cadastrar").mouseenter(function(){
			$("#borda3").animate({height: "30px"}, 300);
		});
		
		$(".cadastrar").mouseleave(function(){
			$("#borda3").animate({height: "0px"}, 300);
		});
		
		$(".entrar").mouseenter(function(){
			$(".entrar").animate({ backgroundColor: red}, 300 );
		});
		
	});
	
	</script>
	</head>
	
	<body>


	
 
	<div id="all">
		<div id="slide"></div>
	
		<div id="top">
			
			<div class="cadastrar"> <a href="cadastro.html">Cadastrar</a> </div>
		
	
		</div>
		
		<div id="copyrigth"><a href="#">Copyright - 2016 Todos Direitos Reservados.</a>
	
	
		
			<div class="imgrodape1 animated bounce"><a href="#"><img src="Icon/twitter4.png" width="100%" height="100%"></a></div>
			<div class="imgrodape2 animated bounce"><a href="#"><img src="Icon/facebook.png" width="100%" height="100%"></a></div>
			<div class="imgrodape3 animated bounce"><a href="#"><img src="Icon/insta.png" width="100%" height="100%"></a></div>
			<div class="imgrodape4 animated bounce"><a href="#"><img src="Icon/snapchat.png" width="100%" height="100%"></a></div>
			<div id="fechar2"><a href="#">X</a></div>
		
		
		</div>
		
		
		<div id="site">
		
		<div id="ponto">
		</div>
		<div id="ponto2">
		</div>
		<div id="ponto3">
		</div>
		<div id="ponto4">
		</div>
		<div id="ponto5">
		</div>
			
		<!--  Border do Cadastrar --> <div id="borda1"></div> <div id="borda2"></div> <div id="borda3"></div>
			
			<div id="divmeio">
			
	
				<p id="p1" style="display:none"> TK Arts </p>
				<p id="p2" style="display:none">Onde sua arte não é apenas uma arte </p>
				<p id="p3" style="display:none"> É algo genial. </p>
				<p id="p4" style="display:none"> Entre ou Cadastre-se. </p>
				<p id="p5" style="display:none"> Agora mesmo. </p>
			
				<!--  Fechar Mascara -->		
				<div id="fechar"><a href="#">X</a></div>
				
				
			
			</div>
			
		
		<div id="container">
		
			
			<p>Entrar no TK Arts</p>
			
			<form action="LoginSite.php" method="POST">
	
				<input type="text" name="login" class="login" placeholder="Email" maxlength="40" style="display:none">
				<input type="text" name="login" class="senha" placeholder="Email" maxlength="40" required>
		
				<input type="password" name="senha" class="login" placeholder="Login" maxlength="40" style="display:none">
				<input type="password" name="senha" class="login" placeholder="Senha" maxlength="30" required>	
				
				<div id="lembrar-me"><input type="checkbox" name="Manter" class="manter" value="csnasyh">Lembrar-me </div> 
				<div id="esqueceu-senha"> Esqueceu a senha? Clique <a href="#">Aqui</a></div>
				<div id="criar-conta">Não tem uma conta? Oque está esperando? Clique <a href="cadastro.html">Aqui</a> </div>
				
				<a href="#"><input type="submit" value="Entrar" class="entrar"></a>		
	
				
			</form>
			
		</div>
		
		
	</div>		
		
</div>

	
	</body>
	</html>
	
	
