# Gradecalculation
Developed by aditya
import java.util.Scanner;
public class grade{
public static void main(String[] args){
Scanner sc = new Scanner(System.in);
System.out.println("Enter the no of marks: ");
int x = sc.nextInt();
if (x > 90){
System.out.println("you got the 'O' grade");
}
else if ( x<90 && x>80){
System.out.println("you got the 'A' grade");
}
else if ( x<80 && x>70){
System.out.println("you got the 'B' grade");
}
else if (x<70 && x>55){
System.out.println("you got the 'C' grade");
}
else
{
System.out.println("you got the 'F' grade");
}
}}
