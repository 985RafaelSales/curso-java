import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc = new Scanner(System.in);
	    
	    int altura = 0;
		int largura = 0;
	    
		System.out.println("digite a altura: ");
		altura = sc.nextInt();
		System.out.println("digite a largura");
		largura = sc.nextInt();
		
		System.out.println(" a area do retangulo:" +largura*altura);
		
