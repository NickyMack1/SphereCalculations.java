# SphereCalculations.java

import java.util.Scanner;

public class SphereCalculations {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter the radius of the sphere
        System.out.print("Enter the radius of the sphere: ");
        double radius = scanner.nextDouble();

        // Calculate the volume of the sphere
        double volume = (4.0 / 3.0) * Math.PI * Math.pow(radius, 3);

        // Calculate the surface area of the sphere
        double surfaceArea = 4 * Math.PI * Math.pow(radius, 2);

        // Print the volume and surface area with four decimal places
        System.out.printf("Volume of the sphere: %.4f\n", volume);
        System.out.printf("Surface area of the sphere: %.4f\n", surfaceArea);

        scanner.close();
    }
}
Enter the radius of the sphere: 360
Volume of the sphere: 195432195.7945
Surface area of the sphere: 1628601.6316
