/public class Cylinder {
int a;
int r;
int h;
int raduis;
int height;
float area;
float volume;
void accept(int a){
this.a = a;
}
void cArea(){
   area = (2*3.14F *r*h)+ (2*3.14F*a*a);
}
 
void cVolume(){
  volume = 3.14F*a*a*h;
}
 
void Display(){
 
System.out.println("Area is " + area);
}
 
}
 
/public class Circle extends Cylinder{
 
 
int b;
 
  void accept1(int b){
  this.b = b;
 
  }
 
  void tArea(){
 
  area = 3014F*a*a;
  }
 
 
}
 
public class test {
    public static void main ( String[] args ){
  System.out.println("Area of circle is ");
 
    Cylinder obj = new Cylinder();
    obj.accept(10);
    obj.cArea();
    obj.Display();
 
     Circle obj1 = new Circle();
    obj1.accept(15);
   obj1.accept1(20);
    obj1.tArea();
    obj1.Display();
 
 
    }
}
 
