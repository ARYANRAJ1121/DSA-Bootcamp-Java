[Video Link](https://youtu.be/lhELGQAV4gg)
package KK01JAVA;

import java.util.Scanner;

public class leapyear {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int year = sc.nextInt();
        boolean isleapyear = false;
        if (year%4==0){
            isleapyear = true;
        } else if (year%4==0&&year%400==0) {
            isleapyear = true;
        }
        if (isleapyear){
            System.out.println(year + " is a leap year");
        }else {
            System.out.println(year + " is not a leap year");
        }

    }
}
## Create flowchart and pseudocode for the following:

1. Input a year and find whether it is a leap year or not.
2. Take two numbers and print the sum of both.
3. Take a number as input and print the multiplication table for it.
4. Take 2 numbers as inputs and find their HCF and LCM.
5. Keep taking numbers as inputs till the user enters ‘x’, after that print sum of all.
