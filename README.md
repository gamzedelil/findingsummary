# findingsummary

package findingsummary;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int k=0;
        int sum=0;

        do {            
            System.out.print( "Enter an even number: ");
           k=input.nextInt();
           
           if( k % 4 == 0){
                sum+=k;
                System.out.print("Summary: "+ sum+"\n") ;

            }else{
                System.out.println("You entered an odd number. ");
                break;
            }

        }while (k>0);
    }
}

// I will check again.
