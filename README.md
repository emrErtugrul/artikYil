# artikYil


import  java.util.Scanner;

public class Main {

    public static void main(String[] args) {
    
        Scanner inp= new Scanner(System.in);
        
        int years,result;
        
        System.out.println("Yıl Giriniz " );
        
        years =inp.nextInt();
        
        result=years%4;
        
        if(result==0){
        
            System.out.println(years +" bir artık yıldır!");
            
        }else {
        
            System.out.println(years +" bir artık yıl değildir!");

        }

    }
}
