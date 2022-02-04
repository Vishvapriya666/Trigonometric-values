# Trigonometric-values
This code is to print the trigonometric values of 30 and 60 degrees using format precision in JAVA

public class FormatDemo {
    public static void main(String[] args) {
        //Display the header of the table
        System.out.printf("%-10s%-10s%-10s%10s%-10s\n", "Degrees", "Radians", "Sine", "Cosine", "Tangent");

        //Display the values for 30 degrees
        int degrees = 30;
        double radians = Math.toRadians(degrees);
        System.out.printf("%-10d%-10.4f%-10.4f%-10.4f%-10.4f\n", degrees, radians, Math.sin(radians), Math.cos(radians), Math.tan(radians));

        //Display the values for 60 degrees
        radians = Math.toRadians(degrees);
        System.out.printf("%-10d%-10.4f%-10.4f%-10.4f%-10.4f\n", degrees, radians, Math.sin(radians), Math.cos(radians), Math.tan(radians));
    }
}
