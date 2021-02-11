import java.util.*;
import java.lang.*;
import java.io.*;
 
/* Name of the class has to be "Main" only if the class is public. */
class Ideone
{
    public static void main( String[] args){
 
int a[] ={1,2,3,4,5};
int i;
try{
 System.out.println("Array contains...");
for(i=0;i<5;i++){
System.out.println(a[i]);
}
}
  catch(ArrayIndexOutOfBoundsException e)
  {
  System.out.println("Array index is out of bound .. try again");
  }
 
System.out.println("OK");
}}
}
