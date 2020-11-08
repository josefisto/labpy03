<p align="center">
	BAHASA PEMROGRAMAN
</p>
<p align="center">
	MODUL PRAKTIKUM 3 PERULANGAN
</p>
<p align="center">
	Dosen : Agung Nugroho, M.Kom
</p>
<p align="center"> 
	<b>Tugas untuk memenuhi syarat penilain pada Pert-7</b>
</p>

<p align="center">
	<img src="Logo/logo.png" alt="UPB" width="500" height="400">
</p>

<p align="center">
                 Nama : Jose Fisto
</p>
<p align="center">
                 NIM : 312010119
</p>
<p align="center">
                 Kelas : TI.20 A.1
</p>

<p align="center">
	<img src="Logo/blank.png" width="20" height="20">
</p>

<p align="center">
	<b>UNIVERSITAS PELITA BANGSA</b>
</p>
<p align="center">
	<b>FAKULTAS TEKNIK</b>
</p>
<p align="center">
	<b>TEKNIK INFORMATIKA</b>
</p>
<p align="center">
	<b>TA 2020 / 2021</b>
</p>

![]()

# Modul Praktikum 3 Perulangan

## Latihan 1: latihan1.py

![Latihan 1](Screenshot/Latihan1.png)

Keterangan syntax di atas dapat di uraikan, yaitu :

![Syntax](Screenshot/Syntax1.png)

Dapat dinyatakan bahwa :

- `from random import random` merupakan data yang akan memberikan hasil acak
- `a = int(input("Masukkan nilai : "))` merupakan data integer untuk menentukan berapa data nilai yang akan di hasilkan
- `b = 0` merupakan data integer
- `for i in range(a):` merupakan perulangan dari data input a ke variable i
- `i = random()` variable i merupakan data a yang hasilnya akan memberikan data acak dengan hasil float
- `b+=1` variable b apabila b = 0 maka di tambahkan 1 dengan sebanyak yang di tentukan pada variable a
- `print('data ke :',b,'==>', i)` menunjukkan hasil output pada layar

Maka Output atau hasil tertampil di layar :

![Output](Screenshot/Output1.png)

## Latihan 2: latihan2.py

![Latihan 2](Screenshot/Latihan2.png)

Keterangan syntax di atas dapat di uraikan, yaitu :

![Syntax](Screenshot/Syntax2.png)

Dapat dinyatakan bahwa :

- `x = 0` merupakan data integer
- `while True:` menyampaikan kondisi perulangan hingga berhenti
- `a=int(input('Masukkan bilangan: '))` a merupakan data integer ditentukan berapa angka yang keluar
- `if x < a :` `x = a` menyatakan kondisi `if` jika x lebih kecil dari a maka nilai x adalah a
- `if a == 0:` `break` kondisi `if` jika hasil variable a adalah 0 maka berhenti menghitung
- `print('Bilangan terbesar adalah =', x)` mencetak hasil x menampilkan hasil data terbesar dari variable a

Maka Output atau hasil tertampil di layar :

![Output](Screenshot/Output2.png)

## Tugas Praktikum 3

![Tugas Praktikum 3](Screenshot/TugasPrak3.png)

Keterangan syntax di atas dapat di uraikan, yaitu :

![Syntax](Screenshot/SyntaxPrak3.png)

Dapat dinyatakan bahwa :

- `a = 100000000` merupakan modal awal
- `for x in range (1,9):` menggunakan fungsi for loop untuk mendata laba bulan hingga bukan ke 8
- `if (x>=1 and x<=2):` `b=a*0` untuk menyatakan kondisi penghasilan laba di bulan pertama dan kedua tidak mendapatkan laba
- `if (x>=3 and x<=4):` `c=a*0.1` menyatakan kondisi hasil laba di bulan ketiga dan keempat sebesar 1%
- `if (x>=5 and x<=6 and x<=7):` `d=a*0.5` menyatakan kondisi hasil laba di bulan kelima hingga bulan ketujuh  sebesar 5%
- `if (x==8):` `e=a*(0.5-0.3)` menyatakan kondisi hasil laba di bulan kedelapan mengalami penuruan sebesar 2%, sehingga laba sebesar 3%. bahwa penurunan laba sebesar 2% adalah 5% dari laba bulan sebelumnya di kurangi dengan laba bulan kedelapan yaitu sebesar 3%
- lalu total keseluruhan data laba dari bulan pertama hingga kedelapan di jumlah dan di cetak di layar

Maka Output atau hasil tertampil di layar :

![Output](Screenshot/OutputPrak3.png)