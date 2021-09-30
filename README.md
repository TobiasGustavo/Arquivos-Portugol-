# Arquivos-Portugol-
//Exercicios Simples Algoritmos, Laços Condicionais, Laços de Repetição, Vetores e Matrizes 
//Lista de exercícios (Laço de repetição)
//Tobias Gustavo Soares - Turma 35 - Campinas 

//PARA
//1- A prefeitura de uma cidade fez uma pesquisa entre 20 de seus habitantes, coletando dados sobre o salário e número de filhos. A prefeitura deseja saber:   
//a) média do salário da população; 
//b) média do número de filhos; 
//c) maior salário; 
//d) percentual de pessoas com salário até R$100,00.  

programa 

{
    
    // A prefeitura de uma cidade fez 
    //uma pesquisa entre 20 de seus habitantes, coletando dados sobre o salário e número de filhos.
    
    
	funcao inicio() 
	
{
		inteiro contador, qtdFilhos, totalFilhos = 0, mediaF = 0, ate100 = 0
		real salario, totalSalario = 0.0, media = 0.0, maiorSalario = 0, percentual = 0
	
		
		
                      		para (contador = 0; contador < 5; contador++) 
		    
		    
		    escreva("\n\n" + contador + "  ª Pessoa\n")
		    escreva("\n\nDigite seu salario: ")
		    leia(salario)
		    
		    escreva("Quantos filhos: ")
		    leia(qtdFilhos)
		    
		    se (salario > maiorSalario) 
{
		        maiorSalario = salario 
}
		    
	              se ( < = 100 ) 
{
	               ate100 += 1 
 }
		    
		    
	             totalFilhos += qtdFilhos
	             totalSalario += salario
		 
  }
  {
		 mediaS = totalSalario / 4
		 mediaF = totalFilhos /  4
		 percentual = (ate100 * 100) / 4 
		 
		 limpa()
		 
		 escreva("\n ********Relatorio *********")
		 escreva ("\nMédia de Salário: ", medias)
		 escreva("\nMedia de Filhos: ", mediaF)
		 escreva("\nMaior Salario: ", maiorSalario)
		 escreva("\nPercentual com salario até R$100,00: ", percentual)
}
}






//2- Desenvolver um sistema que efetue a soma de todos os números ímpares que são  múltiplos de três e que se encontram no conjunto dos números de 1 até 500.

programa
 {
              // Autor: Tobias Gustavo - EX. 2 
       
	       funcao inicio()
	
 { 
	      inteiro resultado = 0, n
	   
	       para( n = 0; n <= 500; n++){
	       se( n % 3 == e  n % 2 != 0){
	       resultado = resultado + n 
	            
  }
  }
                    escreva("O resultado é:\n", resultado) 
}
}
OU 


          programa {
       // Autor: Tobias Gustavo - EX. 2 
       
          funcao inicio()
	
{ 
           inteiro resultado, n= 0 
	   
            para(resultado = 1; resultado < 500; resultado+=2) {
	        
	 se(n % 3 == 0) 
             n += resultado
	            
  }
  }
            escreva("\nTotal: ", resultado, "\n\n")
  }
  }

//Ajustar codigo  



//ENQUANTO
//1- Elaborar um programa que efetue a leitura sucessiva de valores numéricos e apresente no final o total do somatório, a média e o total de valores lidos. O programa deve fazer as leituras dos valores enquanto o usuário estiver fornecendo valores positivos. Ou seja, o programa deve parar quando o usuário fornecer um valor negativo.
























//2- Obtenha um número digitado pelo usuário e repita a operação de multiplicar ele por três  (imprimindo o novo valor) até que ele seja maior do que 100. Ex.: se o usuário digita 5,  deveremos observar na tela a seguinte sequência: 5 15 45 135.

















































//FAÇA...ENQUANTO
//1- Faça um programa que mostre uma contagem na tela de 233 a 456, só que contando de 3 em 3 quando estiver entre 300 e 400 e de 5 em 5 quando não estiver.

           programa
{
	
	funcao inicio()
{
	inteiro num = 233

	faca { 

	escreva(num, "\n")
			
	se (num >= 300 e num <= 400)
 {
	num+= 3
} senao {
	num += 5	
}
			
} enquanto (num <= 456)
	}
}




2- Faça um programa que pegue um número do teclado e calcule a soma de todos os números  de 1 até ele. Ex.: o usuário entra 7, o programa vai mostrar 28, pois  1+2+3+4+5+6+7=28.
programa
{


	funcao inicio()
{
	inteiro num = 7, soma = num

	faca 
{

			escreva(num, " ")
			num -= 1
			soma += num

}            enquanto (num > 0)

	  escreva("\nA soma equivale a: ", soma, "\n\n")
	
}
}



