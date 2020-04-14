- Usando prompt para entrada de informação do usuário
	prompt()
- Exibindo na tela o que foi digitado no prompt
	alert(prompt('Quantos dias você já viveu ? Informe sua idade!')*365)
- Manipular site utilizando a função document
	document.write('Oi')
	document.write(prompt('Quantos anos você tem ?'),' anos.')
- Utilizando variavel
	suaIdade = 35
	document.write(suaIdade * 365, ' dias.')
	
	suaIdade = prompt('Qual a sua idade ?')
	document.write(suaIdade, ' anos é igual a ', suaIdade * 365, ' dias')
- Convertendo texto em número utilizando o parseint()
	document.write(parseInt(prompt('Qual a sua idade ?')))
- Exercício do IMC
	peso = prompt("Informe seu peso.")
	altura = prompt("Informe sua altura. Ex: 1.67")
	imc = peso / (altura * altura)

	if (imc < 17) {
	    alert("Muito abaixo do peso!")
	} else if (imc >= 17 && imc <= 18.49) {
	    alert("Abaixo do peso")
	} else if (imc >= 18.5 && imc <= 24.99) {
	    alert("Peso normal")
	} else if (imc >= 25 && imc <= 29.99) {
	    alert("Acima do peso")
	} else if (imc >= 30 && imc <= 34.99) {
	    alert("Obesidade I")
	} else if (imc >= 35 && imc <= 39.99) {
	    alert("Obesidade II")
	} else {
	    alert("OBESIDADE MÓRBIDA")
	}
- Exercício da média de idades
	guilherme = parseInt(prompt('A idade do Guilherme é: '))
	carol = parseInt(prompt('A idade da Carol é: '))
	marcia = parseInt(prompt('A idade da Márcia é: '))
	patricia = parseInt(prompt('A idade da Patricia é: '))
	soma = ((guilherme + carol + marcia + patricia)/4)
	document.write('A media de idade da família do Guilherme é: '+ soma +' anos')
- Exercício dos anos da avó de 1940
	document.write('A avó da amiga da Maria que nasceu em 1940 tem '+(2020-1940)+' anos de idade.')