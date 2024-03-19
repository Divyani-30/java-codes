# java-codes
All basic java codes
import java.sql.SQLOutput;

public class Varscope {
    static float y; // static variable
    char ch;// non static variable
    public static void main(String args[])
    {
        int x=10;//local variable
        System.out.println("value of local variable x is"+x);
        System.out.printf("value of static variable y ="+y);
        System.out.println(Varscope.y);
        Varscope obj= new Varscope();
        System.out.println("value of static variable y= "+obj.y);
        System.out.println("Value of non-static variable ch="+obj.ch);
    }
}


