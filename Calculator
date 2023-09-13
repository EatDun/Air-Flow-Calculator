import java.lang.Math;
import java.util.Scanner;

class AirFlow {
    
    public static double btuCalc(double b, double f) {
        return b * f;
    }
    
    public static double afCalc(double q, double dT) {
        return q / (1.08 * dT);
    }
    
    public static void main(String[] args) {
        
        Scanner btuInput = new Scanner(System.in);
        
        System.out.println("Please enter BTUs");
        
        double btu = btuInput.nextDouble();
        
        Scanner effInput = new Scanner(System.in);
        
        System.out.println("\nPlease enter furnace efficiency");
        
        double f = effInput.nextDouble();
        
        double eff = f * .01;
        
        Scanner deltaTInput = new Scanner(System.in);
        
        System.out.println("\nPlease enter delta T");
        
        double deltaT = deltaTInput.nextDouble();
        
        double btuAdj = btuCalc(btu, eff);
        
        double af = afCalc(btuAdj, deltaT);
        
        System.out.println("\nAir flow is " + af);
        
    }
}
