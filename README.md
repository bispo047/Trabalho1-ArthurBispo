# Trabalho1-ArthurBispo
trabalho1-ArthurBispo

import java.util.Scanner;

public class module-info.java{
	 
	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);
		String agencia;
		String nomeCliente;
		double saldo;
		int numero;
		
		System.out.println();
		System.out.println();
		System.out.println("digite o numero da conta:");
		numero = sc.nextInt();
		
		System.out.println("digite o numero da agência:");
		agencia = sc.next();
		
		System.out.println("digite seu nome:");
		nomeCliente = sc.next();
		sc.nextLine();
		
		System.out.println("digite seu saldo atual");
		saldo = sc.nextDouble();
		
		System.out.println();
		System.out.printf("bom dia %s, sua agencia é %s, sua conta é %d e o seu saldo é %.2f", nomeCliente, agencia, numero, saldo);
		
		sc.close();
	}
}
