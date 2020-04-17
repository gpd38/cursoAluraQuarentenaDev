- Calculando de outros exercícios no codepen
Ex.: calcular sua idade em dias
	suaidade = prompt("Qual a sua idade ?");
	if(suaidade >= 0){
	  document.write(suaidade, " anos <br>");
	  document.write(suaidade * 365, " dias");
	}else{
	  document.write("Não foi possivel calcular sua idade em dias com o valor informado! ");
	}
- Exercício de quebra de linha
	alert("Oi\ncomo\nvocê\nestá\npulando\nlinha\n?\n")
	document.write("Oi<br>como<br>você<br>está<br>pulando<br>linha<br>?")
- Exercício do combustível
	velocidade = 80
	tempo = 15
	gastoPorKm = 18
	quantidadeDeCombustivel = (velocidade)* (tempo / gastoPorKm)

	document.write("Fulaninho gastou um total de " + quantidadeDeCombustivel + " litros")