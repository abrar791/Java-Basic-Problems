package practice;

import java.util.Scanner;

public class Practice {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.println("Hello, World!");

        System.out.print("Enter your name: ");
        sc.nextLine();
        String name = sc.nextLine();
        System.out.println("Hello, " + name + "!");

        System.out.print("Enter a number: ");
        int num = sc.nextInt();
        System.out.println(num % 2 == 0 ? "Even" : "Odd");

        System.out.print("Enter 3 numbers: ");
        int a = sc.nextInt();
        int b = sc.nextInt();
        int c = sc.nextInt();
        int max = a;
        if (b > max) max = b;
        if (c > max) max = c;
        System.out.println("Maximum: " + max);

        System.out.print("Enter 2 numbers: ");
        double x = sc.nextDouble();
        double y = sc.nextDouble();
        System.out.print("Enter operation (+,-,*,/): ");
        char op = sc.next().charAt(0);
        if(op == '+') System.out.println(x + y);
        else if(op == '-') System.out.println(x - y);
        else if(op == '*') System.out.println(x * y);
        else if(op == '/' && y != 0) System.out.println(x / y);
        else System.out.println("Invalid operation");

        System.out.print("Enter N: ");
        int N = sc.nextInt();
        for(int i = 1; i <= N; i++) System.out.print(i + " ");
        System.out.println();

        System.out.print("Enter number for multiplication table: ");
        int t = sc.nextInt();
        for(int i = 1; i <= 10; i++) System.out.println(t + " x " + i + " = " + (t*i));

        System.out.print("Enter number for factorial: ");
        int f = sc.nextInt();
        int fact = 1;
        for(int i = 1; i <= f; i++) fact *= i;
        System.out.println(f + "! = " + fact);

        System.out.print("Enter N for sum: ");
        int sumN = sc.nextInt();
        int sum = 0;
        for(int i = 1; i <= sumN; i++) sum += i;
        System.out.println("Sum = " + sum);

        sc.close();
    }
}
