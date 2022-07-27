import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner s=new Scanner(System.in);
        int Hour=s.nextInt();
        if(Hour<=12){
            System.out.print("good morning");
                
        }
        else if(12<=Hour&&Hour<=16){
            System.out.print("good afternoon");
        }
        else if (16<=Hour&&Hour<=20){
            System.out.print("good evening");
        }
        else if(20<=Hour&&Hour<=24){
            System.out.print("good night");
        }
        else if(24<=Hour){
            System.out.print("invalid input");
        }
    }
}
