# JavaAssignment
import java.util.Scanner;


public class Assignment {
	Scanner enter = new Scanner (System.in);
	int age;
	String name;
	
public static void main(String[] args) {
	Assignment assign = new Assignment();
	assign.level();
	
}


private void level() {
	System.out.println("Get ready to know your level.");
	
	System.out.println("Enter your name here : ");
	name = enter.nextLine();
	
	
	System.out.println("Enter age here : ");
	age = enter.nextInt();
	
	if (age <= 5)
		System.out.println(name + " , you should be in kindergarten.");
		
	else if (age>5 && age<=12)
		System.out.println(name + " , you should be in Kiddies.");
	
	else if (age>12 && age<=19)
		System.out.println(name + " , you belong to Teenagers");
	
	else if (age>19 && age<=26)
		System.out.println(name + " , proceed to the Youth section.");
	
	else if (age > 35)
	System.out.println(name + ", proceed to the Adult.");
	
	
	}
}

