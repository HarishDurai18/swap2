import java.util.Scanner;
public class swap2{ 

 public static void main(String args[]){

   System.out.println("Before swap");

  int x=10;
  int y=20;



  System.out.println("value ofx:"+x);
  System.out.println("value ofy:"+y);
  
  x=x+y; 
  y=x-y;
  x=x-y;

  System.out.println("After swap");

  System.out.println("value ofx:"+x);
  System.out.println("value ofy:"+y);





  }

 }
