# exJava
Exercicio Java
package tstee;

import java.util.Scanner;

public class teste {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		 
		double valor = 50.0;
		var tempo = 100; 
		Scanner sc = new Scanner(System.in);
		int minutos =  sc.nextInt() ;
		
		if (minutos > 100) {
			valor = valor + (minutos - 100)*2.0;
		}
		
		System.out.printf("Valor da conta = R$%.2f%n", valor);
		
	}

}
