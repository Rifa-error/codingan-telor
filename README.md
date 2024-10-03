import java.util.Scanner;

public class telor {
    public static void main(String[] args) {
        Scanner inputan  = new Scanner(System.in);
        System.out.print("Masukan (kg)telor yang dibeli: ");
        Double Kilotelor = inputan.nextDouble();
        
        System.out.print("Masukan Uang Bayar");
        Double UangBayar = inputan.nextDouble();

        double HargaTelur = Kilotelor * 28000;
        double kembalian = UangBayar - HargaTelur;

        System.out.println("Harga telor per kilogram: " + kembalian);
    }
}


import java.util.Scanner;

public class lingkaran {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        // Konversi celcius ke fahrenheit
        System.out.print("masukan suhu dalam celcius ");
        Double celcius = input.nextDouble();
        Double fahrenheit = (celcius * 9 / 5) + 32;
        System.out.println("Suhu dalam fahrenheit: " + fahrenheit);

        // Menghitung keliling lingkaran
        System.out.print("Masukan jari-jari lingkaran");
        Double jarijari = input.nextDouble();
        Double keliling = 2 * Math.PI * jarijari;
        System.out.println("keliling lingkaran: " + keliling);

        // Menghitung luas persegi panjang
        System.out.print(" Masukan panjang persegi panjang ");
        Double panjang = input.nextDouble();
        System.out.print("Masukan lebar persegi panjang ");
        Double lebar = input.nextDouble();
        Double luas = panjang * lebar;
        System.out.println("Luas persegi panjang: " + luas);

        // Menghitung volume kubus
        System.out.print("Masukan sisi kubus ");
        Double sisi = input.nextDouble();
        Double volume = sisi * sisi * sisi;
        System.out.println("volume kubus: " + volume);

        input.close();
    
    }
}
