# Program Mencari Bilangan Terbesar Dari 3 Bilangan
Program sederhana untuk mencari nilai terbesar dari 3 bilangan yang dimasukkan.

## Rincian Program
program ini ditulis menggunakan bahasa python dan memiliki fungsi sebagai berikut:

Menggunakan 'int' untuk mendefinisikan input.
Memanfaatkan fungsi 'if' untuk membuat skenario pengeliminasi fungsi pad input.
Memanfaatkan fungsi 'else' jika skenarionya adalah sebaliknya.

## Flow chart
![FLOWCHART](FLOWCHART_2.PNG)

## Kode Mencari Bilangan Terbesar Dari 3 Bilangan
````
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))

if a > b:
    if a > c:
        print("Bilangan A adalah terbesar")
    else:
        print("Bilangan C adalah terbesar")
else:
    if b > c:
        print("Bilangan B adalah terbesar")
    else:
        print("Bilangan C adalah terbesar")
````

## Contoh Tampilan Output
````
Masukkan bilangan A: 20
Masukkan bilangan B: 87 
Masukkan bilangan C: 59
B adalah terbesar
Bilangan terbesar adalah: 87
````

## Penjelasan Kode
Program ini menjelaskan bilangan terbesar dari 3 bilangan yang di input oleh pengguna dengan cara:

masukan bilangan A, B, C setelah masukan bilangan kemudian, cek bilangan mana yang mempunyai nilai terbesar

A > B? if yes (bilangan terbesar adalah A) kemudian A > C if yes bilangan terbesar adalah A If no (bilangan terbesar adalah c)

B > SEBUAH? if yes (bilangan terbesar adalah B) kemudian B > C if yes bi;amgan terbesar adalah B if no (bilangan terbesar adalah C).



# Program Mencari Bilangan Terbesar Menggunakan Looping Sederhana
Program sederhana untuk mencari nilai terbesar dari kumpulan bilangan yang diinputkan menggunakan perulangan sederhana menggunakan pernyataan while dan break.

## Rincian Program
Program ini ditulis dalam bahasa Python dan memiliki fitur sebagai berikut:

- Menggunakan loop while True untuk perulangan yang tidak terbatas.
- Memanfaatkan pernyataan break untuk mengakhiri program eksekusi.
- Bandingkan setiap masukan dengan nilai maksimum yang sudah ada.
- Menampilkan angka tertinggi yang berhasil ditemukan.

## Flowchart 


