# prime
#### Display Prime Number

     public class MyClass {

     public static void main(String[] args) {
 
     int num = 600, count, i;
  
     for ( i = 500; i <= num; i++) {
  
     count = 0;
   
     for (int j = 2; j <= i / 2; j++) {
   
     if (i % j == 0) {
    
     count++;
     
     break;
     
     }
    
     } 
   
     if (count == 0) {
   
     System.out.println(i);
    
     }
  
     }
  
     }
 
     }
