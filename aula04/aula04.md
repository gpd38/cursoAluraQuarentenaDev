- Aprendendo sobre concatenação
	valorcorrida = 40
	alert('Sua corrida deu '+ valorcorrida.toFixed(2))
- Aprendendo a utilizar casas decimais
	valorcorrida = 40
	alert('Sua corrida deu '+valorcorrida)
- Aplicativo de trnsporte no codepen
	distancia = prompt("Qual a distância percorrida em Km ?")
	tempo = prompt("Qual foi o tempo da viagem?")

	if(distancia >= 0 && tempo >= 0){
		valorcorrida = 2 + distancia * 1.4 + tempo * 0.26
		document.write("O valor da sua corrida foi: R$ " + valorcorrida.toFixed(2))
	}else{
		document.write("Alguns valores informados estão incorretos !")
	}