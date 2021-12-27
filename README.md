# dio-desafio-github-repositorio
Desafio de Projeto de Git / GitHub - DIO

#---------------------------------------#
## Exemplo Calculadora.java ##
### Usando JOptionPane como entrada de dados ###

import javax.swing.JOptionPane;

public class **TabuadaForJPane** {
	
	public static void main(String[] args) {
		
		int num,cont;
		
		num = Integer.parseInt(JOptionPane.showInputDialog(null,"Entre com um número de 0 a 10:"));
		
		System.out.println("=====TABUADA DE MULTIPLICAÇÃO======\n");
		
		for (cont = 0;cont <=10;cont++) {
    
			System.out.println(num + "\tx\t" + cont + "\t=\t" + num*cont);
      
		 }
	  }
	}


