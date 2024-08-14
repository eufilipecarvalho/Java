package start;

import java.util.Scanner;

public class hello {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in); 

		System.out.println("informe um número: ");
		double num = sc.nextDouble();
		
		System.out.println("informe um nome: ");
		String nome = sc.next();
		
		System.out.println("númro digitado: " + num); 
		
		System.out.println("nome dogotado: " + nome);
		
		sc.close();
	}

}
