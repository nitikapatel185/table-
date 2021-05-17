# table-
table  in array by java
package firstproject;
import java.util.Scanner;
public class table {
	public static void main(String args[]) {
		int num;
		Scanner input=new Scanner(System.in);
		System.out.println("Enter any number=");
		num=input.nextInt();
		for(int i=1;i<=10;i++) {
		System.out.println(num+"*"+i+"="+num*i);
		}
	}
}
