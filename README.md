# Java-LoopsII-HackerRank-
import java.util.*;
public class javaloopsII{
  public static void main(String[]args){
    Scanner sc=new Scanner(System.in);
    int c=0;
    int q=sc.nextInt();
    int a=sc.nextInt();
    int b=sc.nextInt();
    int n=sc.nextInt();
    double y=b*Math.pow(2,c-n);
    double x=0;
    for(c=n;c>=0;c--){
      x=x+y;
      System.out.print(a+x+" ");
    }
    
  }
}

//Contributed By: DIN MOHAMMAD ZUBAIR
