# PP-3.9

/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package pp.pkg3.pkg9;

/**
 *
 * @author Derek
 */
import java.util.Random; 
public class PP39 {
    
public static void main(String[] args) {
int r; int h; double vol; double area;
Random rand = new Random();

r = rand.nextInt(10) + 1; 
h = rand.nextInt(10) + 1;

vol = Math.PI * Math.pow(r, 2) * h; 
area = (2 * Math.PI * r * h) + (2 * Math.PI * Math.pow(r,2));

System.out.println("radius = " + r); 
System.out.println("height = " + h); 
System.out.println("volume = " + vol); 
System.out.println("area = " + area);

}
}
