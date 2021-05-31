# Soma_Inteiros
import java.util.Scanner;

public class Soma_Inteiros {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner scanner = new Scanner(System.in);
		
		int number1;
		int number2;
		int soma;
		
		System.out.print("Digite o primeiro número");
		number1 = scanner.nextInt();
		
		System.out.print("Digite o segundo número");
		number2 = scanner.nextInt();
		
		
		soma= number1 + number2;
		
		System.out.println("A soma é igual a " +soma);
		
	}

}
