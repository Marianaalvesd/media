# media
Cálculo Média Artimética
//Função do algoritmo: calcular media aritmetica
//Autora: Mariana Alves

programa
{
	
	funcao inicio()
	{
		real nota1,nota2,nota3,nota4,media
		cadeia nome

		escreva("Digite o seu nome:")
		leia(nome)
		escreva("Digite nota 1:")
		leia(nota1)
		escreva("Digite nota 2:")
		leia(nota2)
		escreva("Digite nota 3:")
		leia(nota3)
		escreva("Digite nota 4:")
		leia(nota4)


		media = (nota1+nota2+nota3+nota4)/4

		escreva("Sua média é:" + media)
		//verifica se a media é igual ou maior que 7
		se (media>=7){
			escreva("\n" + "Parabéns!!" + nome + " Você foi aprovado!")
		}
		
		//verifica se a media é menor que 7
		
		senao {
			escreva("\n" + "Infelizmente você foi reprovado")
		}
		
		


		
		
	}
