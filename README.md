31.polymorphism
*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package main;

/**
 *
 * @author 1BSCCSA46
 */
public class Main {
    public int addition(int x, int y) {
    return x + y;
  }
     public int addition(int x, int y, int z) {
    return x + y + z;
  }
    public double addition(double x, double y) {
    return x + y;
  }

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
             Main number = new Main();
      int res1 = number.addition(444, 555);
    System.out.println("Addition of two integers: " + res1);

    int res2 = number.addition(333, 444, 555);
    System.out.println("Addition of three integers: " + res2);
   
    double res3 = number.addition(10.15, 20.22);
    System.out.println("Addition of two doubles: " + res3);
  }

}

run:
Addition of two integers: 999
Addition of three integers: 1332
Addition of two doubles: 30.369999999999997
BUILD SUCCESSFUL (total time: 0 seconds)



