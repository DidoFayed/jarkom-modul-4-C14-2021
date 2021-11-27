# jarkom-modul-4-C14-2021

Praktikum Jaringan Komputer Modul 4 - Subnetting & Routing
### Nama Anggota Kelompok:
1. 05111940000059 	Dido Fabian Fayed <br>
2. 05111940000074	Nur Ahmad Khatim <br>
3. 05111940000162	Ramadhan Arif Hardijansyah

## VLSM
### Subnetting
1. Melakukan subnetting pada topologi yang diberikan. Sehingga terbentuklah 13 subnet di dalam topologi seperti pada gambar berikut. 
![CIDR](https://github.com/DidoFayed/jarkom-modul-4-C14-2021/blob/main/CIDR/CIDR_1.png)
2. Menentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan lmelakukan labelling netmask berdasarkan jumlah IP yang dibutuhkan.
- <img width="282" alt="Screen Shot 2021-11-27 at 16 29 12" src="https://user-images.githubusercontent.com/80528848/143675869-c9213a1c-df96-4e57-afe3-0dc91fd8e664.png">
3. Subnet besar yang dibentuk memiliki NID 10.21.0.0 dengan netmask /19. Selanjutnya menghitung pembagian IP berdasarkan NID dan netmask tersebut menggunakan pohon seperti gambar berikut. 
- <img width="997" alt="Screen Shot 2021-11-27 at 16 36 09" src="https://user-images.githubusercontent.com/80528848/143676009-1e1752ff-4bb0-40dd-a616-9bb021e9c04a.png">
<img width="969" alt="Screen Shot 2021-11-27 at 16 38 31" src="https://user-images.githubusercontent.com/80528848/143676073-0c0a7ebf-453f-4aa1-841b-092563efae4b.png">

### CPT VLSM
1. Membuat topologi di CPT. 
- foto
2. Mengatur IP untuk masing-masing interface yang ada di setiap device sesuai dengan pembagian subnet pada pohon VLSM.
3. ...

## CIDR
### Subnetting
1. Menentukan subnet yang ada dalam topologi dan melakukan labelling netmask terhadap masing-masing subnet. Hasilnya ada pada gambar berikut. 
![CIDR](https://github.com/DidoFayed/jarkom-modul-4-C14-2021/blob/main/CIDR/CIDR_1.png)
![CIDR](https://github.com/DidoFayed/jarkom-modul-4-C14-2021/blob/main/CIDR/CIDR_2.png)
![CIDR](https://github.com/DidoFayed/jarkom-modul-4-C14-2021/blob/main/CIDR/CIDR_3.png)
![CIDR](https://github.com/DidoFayed/jarkom-modul-4-C14-2021/blob/main/CIDR/CIDR_4.png)
![CIDR](https://github.com/DidoFayed/jarkom-modul-4-C14-2021/blob/main/CIDR/CIDR_5.png)
![CIDR](https://github.com/DidoFayed/jarkom-modul-4-C14-2021/blob/main/CIDR/CIDR_6.png)
![CIDR](https://github.com/DidoFayed/jarkom-modul-4-C14-2021/blob/main/CIDR/CIDR_7.png)
2. Dari proses penggabungan yang telah dilakukan, didapatkan sebuah subnet besar yang memiliki NID 10.21.0.0 dengan netmask /16.
3. Selanjutnya menghitung pembagian IP dengan pohon berdasarkan penggabungan subnet yang telah dilakukan. 
<img width="754" alt="Screen Shot 2021-11-27 at 15 52 35" src="https://user-images.githubusercontent.com/80528848/143676294-5b1c70f1-ca3f-4293-92f2-fe76b1fe7e73.png">
