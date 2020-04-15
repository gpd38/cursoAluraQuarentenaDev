- Exercício do combustível dinâmico
	distancia = prompt("Qual a distância percorrida ?")
	tempo = prompt("Qual foi o tempo da viagem?")

	if(distancia >= 0 && tempo >= 0){
		valorcorrida = 2 + distancia * 1.4 + tempo  * 0.26
		document.write("O valor da sua corrida foi: R$ " + valorcorrida.toFixed(2))
	}else{
		document.write("Alguns valores informados estão incorretos !")
	}