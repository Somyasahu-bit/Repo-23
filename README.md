# Repo-23
Print ASCII value of character
//Print ASCII value of character
import java.util.Scanner;
class ASCII{
    public static void main (String[] args){
    char ch;
    System.out.println("Enter any character");
    Scanner r=new Scanner(System.in);
    ch = r.next().charAt(0);
    int a=ch;
    System.out.println("ASCII value of" +ch+"is"+a);
    }
}

