/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package javaapplication2;

import java.util.Scanner;

/**
 *
 * @author NITRO V 15
 */
public class tugas6 {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        boolean validInput = false;
        double diameter = 0;

        while (!validInput) {
            System.out.println("======Perhitungan Lingkaran======");
            System.out.print("Masukkan nilai diameter lingkaran: ");

            if (scanner.hasNextDouble()) {
                diameter = scanner.nextDouble();
                if (diameter > 0) {
                    validInput = true;
                } else {
                    System.out.println("Nilai Diameter Tidak Sesuai. Nilai harus lebih besar dari 0.");
                }
            } else {
                System.out.println("Nilai Diameter Tidak Sesuai. Harap masukkan angka.");
                scanner.next(); // clear the invalid input
            }
        }

        double radius = diameter / 2;
        double luas = Math.PI * Math.pow(radius, 2);
        double keliling = 2 * Math.PI * radius;

        System.out.println("\n======Hasil Perhitungan Lingkaran======");
        System.out.printf("Jari-jari lingkaran = %.2f%n", radius);
        System.out.printf("Luas lingkaran = %.2f%n", luas);
        System.out.printf("Keliling lingkaran = %.2f%n", keliling);
    }
}


