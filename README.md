# Aulas_FPB_Junio
import java.util.Scanner;

public class Exercíxio {

	public static void main(String[] args) {
		// Aprovação de crédito
Scanner sc = new Scanner(System.in);

System.out.println("Informe o seu salário :");
double sl = sc.nextDouble();

double sl1 = (sl * 30) / 100;

System.out.println("Informe o valor da prestação : ");
double prest = sc.nextDouble();

if (prest > sl1) {System.out.println(" Crédito não aprovado! ");} 

else {System.out.println(" Crédito aprovado =)!" );}


 
	}

}
