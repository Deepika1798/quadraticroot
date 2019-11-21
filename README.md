# quadraticroot
import java.io.*;
import java.lang.Math;
class root
{
    public static void main(String args[])throws Exception
    {
       BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
        
        int a,b,c,d;
        double root1,root2;
        System.out.println("enter 3 numbers");
        a=Integer.parseInt (br.readLine());
        b=Integer.parseInt(br.readLine());
        c=Integer.parseInt(br.readLine());
       d=b*b-4*a*c;
       root1=(-b-(Math.sqrt(d)))/(2*a);
       root2=(-b+(Math.sqrt(d)))/(2*a);
        System.out.println ("the first root "+root1);
        System.out.println ("the second root "+root2);
    }
}
