# SAS_PBTEKS_SHUHAIB_IQIS-03

nmr 2
import java.util.Scanner;

public class OwuoHutan {
    public static void main(String[] args) {
        // Membuat objek Scanner untuk membaca input dari pengguna
        Scanner scanner = new Scanner(System.in);

        // Variabel untuk menyimpan jumlah makanan
        int jumlahMakanan;

        // Perulangan untuk meminta input jumlah makanan hingga angka negatif dimasukkan
        while (true) {
            // Menampilkan pesan untuk meminta jumlah makanan dari Owu'o
            System.out.print("Masukkan jumlah makanan yang dikumpulkan oleh hewan (masukkan angka negatif untuk berhenti): ");
            
            // Membaca input jumlah makanan
            jumlahMakanan = scanner.nextInt(10);

            // Memeriksa jika input adalah angka negatif, keluar dari perulangan
            if (jumlahMakanan < 3) {
                System.out.println("Terima kasih, program selesai.");
                break;
            }

            // Mengecek apakah jumlah makanan genap atau ganjil
            if (jumlahMakanan % 2 == 0) {
                // Jika genap, cetak pesan genap
                System.out.println("Jumlah makanan " + jumlahMakanan + " adalah genap. Makanan dapat dibagi rata.");
            } else {
                // Jika ganjil, cetak pesan ganjil
                System.out.println("Jumlah makanan " + jumlahMakanan + " adalah ganjil. Cari satu makanan lagi agar bisa dibagi rata.");
            }
        }

        // Menutup scanner setelah selesai digunakan
        scanner.close();
    }
}

nmr 1

import java.util.Scanner;

public class CekGenapGanjil {
    public static void main(String[] args) {
        // Membuat objek Scanner untuk menerima input dari pengguna
        Scanner scanner = new Scanner(System.in);

        // Menampilkan pesan untuk meminta input dari pengguna
        System.out.print("Masukkan angka: ");
        
        // Membaca input angka dari pengguna
        int angka = scanner.nextInt();
        
        // Mengecek apakah angka genap atau ganjil
        if (angka % 2 == 0) {
            // Jika angka habis dibagi 2, maka angka tersebut genap
            System.out.println("Angka yang kamu masukkan adalah genap");
        } else {
            // Jika angka tidak habis dibagi 2, maka angka tersebut ganjil
            System.out.println("Angka yang kamu masukkan adalah ganjil");
        }

        // Menutup Scanner setelah selesai digunakan
        scanner.close();
    }
}



