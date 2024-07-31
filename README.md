# BINARY-SEARCH-IN-JAVA
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
      int []a={1,2,3,4,5,6,7,8,87,90};
      Scanner sc=new Scanner(System.in);
      int k=sc.nextInt();
      int l=10;
      int n=0;
      for(int i=0;i<l;){
          if (a[(i+l)/2]==k){
              System.out.println("number found");
              n=1;
              break;
          }     
          if (a[(i+l)/2]>k){
              l=(i+l)/2;
            
            }
          else
            i=(i+l)/2;
        }
      if (n==0){
           System.out.println("number not found");
        }
    }
}
