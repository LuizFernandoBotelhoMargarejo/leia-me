# leia-me
ExercicioConvertendonumeros.java

import java.util.Scanner;
public class Lista01_Exercicio_Bonus{
	public static void main(String[] args) {
		Scanner leitor = new Scanner(System.in);
		System.out.println("Informe um numero que queira inverter : ");
		int numero = leitor.nextInt();
		int numeroinvertido = 0;
		while(numero > 0){
			numeroinvertido = numeroinvertido * 10;
		    numeroinvertido = numeroinvertido + (numero % 10);
			numero =numero /10;
		}
		System.out.println(numeroinvertido);
		
	}
}
