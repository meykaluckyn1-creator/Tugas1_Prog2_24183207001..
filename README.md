# Mahasiswa.java
package mahasiswa;
public class Mahasiswa {
    String nama;
    String nim;
    String jurusan;
    
    public Mahasiswa(String nama, String nim, String jurusan) {
        this.nama = nama;
        this.nim = nim;
        this.jurusan = jurusan;
    }

    public void tampilkanData() {
        System.out.println("=== Data Mahasiswa ===");
        System.out.println("Nama    : " + nama);
        System.out.println("NIM     : " + nim);
        System.out.println("Jurusan : " + jurusan);
        System.out.println("---------------------");
    
    }
    
}


# MainClass.java
public class MainClass {
    public static void main(String[] args) {
        Mahasiswa mhs1 = new Mahasiswa("Meyka Lucky n", "2418003", "Pendidikan Teknologi Informasi");
        Mahasiswa mhs2 = new Mahasiswa("Cester Marcelin", "2418004", "Ilmu Hukum");
        
        mhs1.tampilkanData();
        mhs2.tampilkanData();
        
    }
}

# hasil.java
=== Data Mahasiswa ===
Nama    : Meyka Lucky n
NIM     : 2418003
Jurusan : Pendidikan Teknologi Informasi
---------------------
=== Data Mahasiswa ===
Nama    : Cester Marcelin
NIM     : 2418004
Jurusan : Ilmu Hukum
---------------------
BUILD SUCCESSFUL (total time: 0 seconds)

# identitas mahasiswa
Meyka Lucky Nazarulloh
24183207001
PTI

# Penjelasan
1.Class Mahasiswa
Class ini berfungsi sebagai template atau blueprint untuk membuat objek mahasiswa.
Di dalamnya terdapat atribut (variabel) dan method (fungsi).
- Konstruktor ini digunakan untuk menginisialisasi (memberi nilai awal) atribut ketika objek baru dibuat.
Kata kunci this digunakan untuk membedakan antara variabel instance (this.nama) dan parameter dari konstruktor (nama).
- Method ini berfungsi untuk menampilkan data mahasiswa ke layar.
Setiap objek mahasiswa bisa memanggil method ini untuk menampilkan datanya masing-masing.
2. Class MainClass
Class ini berisi method utama main() — yaitu titik awal eksekusi program Java.
Kedua baris ini memanggil method tampilkanData() untuk menampilkan data setiap mahasiswa.
