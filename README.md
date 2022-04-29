# curso-java
package exercicio_9;
import java.util.Scanner;
public class exercicio_ {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		double custodocarro=0;
		double impostos=0;
		double percentual=0;
		System.out.println("dgite o valor");
		custodocarro=sc.nextDouble();
		System.out.println("digite o valor");
		impostos=sc.nextDouble();
		System.out.println("digite um valor");
		percentual=sc.nextDouble();
		System.out.println(custodocarro*100/impostos/percentual);

	}

}
