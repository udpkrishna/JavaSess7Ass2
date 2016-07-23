# JavaSess7Ass2

package Session7;

import java.util.Scanner;

public class Sess7Ass2 {
	public static void main(String[] args) {
		String data;
		System.out.println("Enter alphanumeric");
		Scanner read=new Scanner (System.in);
		data=read.nextLine();
		try{
					int num=Integer.parseInt(data);
		System.out.println("Number in the entered string is "+num);
		}catch(NumberFormatException e){
			System.out.println("Does not contain parsable integer !!!");
		}		
	}
}
