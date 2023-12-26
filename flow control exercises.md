1)java program to get a number from the user and print whether it is positive or negative
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("INPUT:");
        int n = sc.nextInt();
        if (n>=0) {
            System.out.println("Positive");
        }
        else {
            System.out.println("Negative");
        }
    }
2)take three numbers from the user and print the greatest number
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Input the first number:");
        int num1 = sc.nextInt();

            System.out.println("Input the second number:");
       int num2 = sc.nextInt();
            System.out.println("Input the third number:");
            int num3 = sc.nextInt();
            if (num1 > num2)
                if(num2 > num3)
                    System.out.println("The greatest: " +num1);
            if (num2 > num1)
                if (num2 > num3)
                    System.out.println("The greatest: " +num2);
            if (num3 > num1)
                if (num3 > num2)
                    System.out.println("The greatest: " +num3);
    }
}
4)write a java program to display the first 10 natural numbers
public class Main {
    public static void main(String[] args) {
        int i;
        for (i=1;i<=10;i++)
        System.out.print(" "+i);
    }
}
5)write a program in java to input 5 numbers from the keyboard and find their sum and average
import java.util.Scanner;

 class Main {
    public static void main(String[] args) {
        int i,n=0,s=0;
       double avg;
        {
            System.out.println("Input the 5 numbers:" );
        }
        for (i=0;i<5;i++)
        {
            Scanner sc = new Scanner(System.in);
            n=sc.nextInt();
            s+=n;
        }
        avg=s/5;
        System.out.println("The sum of 5 no is:"+s+"\nThe Average is:"+avg);
    }
}
6)write a program in java to take employee information
import java.util.Scanner;

 class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter name:");
        String name=sc.next();
        System.out.println("Enter salary:");
        double sal=sc.nextDouble();
        System.out.println("Enter age:");
        int age=sc.nextInt();
        System.out.println();
        System.out.println("Name is:"+name);
        System.out.println("Salary is:"+sal);
        System.out.println("Age is:"+age);
    }
}
