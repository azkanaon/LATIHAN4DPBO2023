# LATIHAN4DPBO2023
## Identitas
- Nama : Muhammad Azka Atqiya
- NIM  : 2100812
- Kelas : C2 2021

## Janji
Saya [Muhammad Azka Atqiya] dengan NIM 2100812 mengerjakan Latihan 4 
Praktikum DPBO dalam mata kuliah [Desain Pemrograman Berorientasi Objek] untuk 
keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah 
dispesifikasikan. Aamiin.

## Desain Program
![image](https://user-images.githubusercontent.com/90915678/223436825-f81758e6-159b-44b5-ba58-99d2b8f1cdb4.png)
### Alasan Desain
1. Setelah membaca mengenai sivitas akademik, saya menemukan bahwa sivitas akademik merupakan kumpulan orang-orang, maka dari itu saya menyimpulkan bahwa sivitas akademik merupakan anak dari Human. Alasan saya memasangkan mahasiswa sebagai child dari sivitas akademik karena sivitas akademik terdiri dari mahasiswa, dosen, TU, dll sehingga sudah sangat jelas bahwa mahasiswa adalah bagian dari sivitas akademik.
2. Alasan Prodi has a mahasiswa, course, dan dosen adalah karena pada dunia nyata, mahasiswa, dosen, dan course terhubung melalui prodi. Misalnya mahasiswa A mengontrak matkul Z dengan dosen X, nah pasti antara mahasiswa A, dosen X dan matkul Z ada yang menghubungkan, yaitu Prodi
### Penjelasan Kelas
- Class Human
  - Atribut :
    - nik => nik orang
    - nama => nama orang
    - jenis kelamin => jenis kelamin orang
  - Method :
    - Human => Konstruktor
    - get... => Memanggil nilai atribut
    - set... => Assign nilai ke atribut

- Class Sivitas Akademik
  - Atribut :
    - asalUniv => asalUniv orang
    - emailEdu => email orang
  - Method :
    - SivitasAkademik => Konstruktor (disini saya juga memanggil variabel yang ada di parentnya)
    - get... => Memanggil nilai atribut
    - set... => Assign nilai ke atribut

- Class Mahasiswa
  - Atribut :
    - nim => nim mahasiswa
    - fakultas => fakultas orang
  - Method :
    - Mahasiswa => Konstruktor (disini saya juga memanggil variabel yang ada di parentnya, yang artinya memanggil parentnya si parent juga)
    - get... => Memanggil nilai atribut
    - set... => Assign nilai ke atribut
    
- Class Dosen
  - Atribut :
    - nip => nip dosen
    - fakultas => fakultas dosen
    - keahlian => keahlian dosen
    - pendidikanAkhir => pendidikan terakhir dosen
  - Method :
    - Dosen => Konstruktor (disini saya juga memanggil variabel yang ada di parentnya, yang artinya memanggil parentnya si parent juga)
    - get... => Memanggil nilai atribut
    - set... => Assign nilai ke atribut
    
- Class Course
  - Atribut :
    - namaMatkul => nama mata kuliah
  - Method :
    - Course => Konstruktor ()
    - get... => Memanggil nilai atribut
    - set... => Assign nilai ke atribut
    
- Class Prodi
  - Atribut :
    - namaProdi => nama mata kuliah
    - kode => kode dari prodi tersebut
    - mahasiswa => mahasiswa yang ada pada prodi tersebut
    - dosen => dosen yang ada pada prodi tersebut
    - course => course yang ada pada produ tersebut
  - Method :
    - Course => Konstruktor (disini memanggil juga init pada kelas mahasiwa, dosen, dan course yang disimpan pada variabel tertentu)
    - get... => Memanggil nilai atribut
    - tidak ada set karena pada kasus ini tidak ada perubahan yang dilakukan sehingga saya berpikir untuk tidak menuliskan set
    
    
## Alur Program
1. Masukkan berapa jumla dosen, mahasiswa, dan course yang ingin dimasukkan
2. Inputan dimasukkan ke variabel yang meng-append ke kelas masing-masing
3. Setelah sudah masuk ke variabel dengan kelas masing-masing, append semua variabel ke variabel yang meng-append kelas prodi
4. Hasil ditampilkan

## Dokumentasi
Ini masukkan
![image](https://user-images.githubusercontent.com/90915678/223441746-4e38d7fd-4c2c-4484-af4a-45c0f16eeece.png)
ini Outputnya
![image](https://user-images.githubusercontent.com/90915678/223441871-1799c7fa-c4e4-484a-8348-5ede22caf568.png)

