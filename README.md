# Tugas-ke-7
Nama    : Bayu Maulana Ayassy

NIM     : 312210166

Kelas   : TI.22.A1

### DAFTAR ISI <br>
| No | Description | Link |
| ----- | ----- | ---- |
| 1 | Lab 2 : Struktur Kondisi | [Click Here](#Lab-2-Struktur-Kondisi) |
| 2 | Lab 3 : Perulangan | [Click Here](#Lab-3-Perulangan) |
| 3 | Labpy02 | [Click Here](#Labpy02) |
| 4 | Labpy03 | [Click Here](#Labpy03) |
| 5 | Author  : Bayu Maulana Ayassy | [Click Here](#Author-Yoga-Pratama) |




# KONDISI DAN PERULANGAN

## Lab 2 Struktur Kondisi

### Latihan 1

• Buat program sederhana dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if!

Langkah - langkah 

1. Buat programnya terlebih dahulu seperti gambar di bawah ini
![Lat1struktur](https://user-images.githubusercontent.com/115678251/200256416-ecc17c2b-42ba-4e9a-8b52-051d78422f29.png)




```
# menentukan bilangan
print('Menentukan bilangan terbesar dari 2 bilangan')
a = int(input("Masukkan nilai A:"))
b = int(input("Masukkan nilai B:"))
if a > b:
    print("A =", a, "yang terbesar")
elif b > a:
    print("B=", b, "yang terbesar")
````

2. Hasil Run 
![2022-11-07 (17)](https://user-images.githubusercontent.com/115678251/200258069-33e3e583-2eed-4796-9e4e-9581839104b8.png)



### Latihan 2
• Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.

Langkah - langkah
1. Buat programnya terlebih dahulu seperti gambar di bawah ini

![1](https://user-images.githubusercontent.com/115678251/200266155-2f851bbd-b582-4b79-9482-856c9e92657e.png)


```
print("_____Mengurutkan bilangan dari yang terkecil ke yang terbesar_____")
print("Masukan 3 bilangan yang akan diurutkan:")
a = int(input("masukkan bilangan 1 = "))
b = int(input("masukkan bilangan 2 = "))
c = int(input("masukkan bilangan 3 = "))

if a < b and a < c:
    if b < c:
        print(a, b, c)
    else:
        print(a, c, b)
elif b < a and b < c:
    if a < c:
        print(b, a, c)
    else:
        print(b, c, a)
else:
    if a < b:
        print(c, a, b)
    else:
        print(c, b, a)
````

2. Hasil Run

![2](https://user-images.githubusercontent.com/115678251/200266282-f12e9cbe-9cea-41ca-8f1e-c164b4c19286.png)



## Lab 3 Perulangan

### Latihan 1
• Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:



Langkah - langkah
1. Buat programnya terlebih dahulu seperti gambar di bawah ini

![200156842-e133051b-af75-49df-b5aa-a65e91fc198d](https://user-images.githubusercontent.com/115678251/200262134-ca2f0aa2-9477-49c8-8ee3-834e75e59cf2.png)


```
for i in range(0,10):
    print()
    print(i, end="\t")
    for j in range(1,10):
        print(i+j,end="\t")
````
2. Hasil Run

![200156901-955f6dd0-e93f-4973-8440-395f6ac3d894](https://user-images.githubusercontent.com/115678251/200262190-475b0f3f-6a5a-40b9-b140-9897aa18b330.png)


### Latihan 2
• Tampilkan n bilangan acak yang lebih kecil dari 0.5.

• nilai n diisi pada saat runtime

• anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya

Langkah - langkah
1. Buatlah programnya terlebih dahulu seperti gambar dibawah ini

![1](https://user-images.githubusercontent.com/115678251/200263247-cb5f88ca-57ab-49f1-b656-4927dd04e270.png)


```
from random import random

n = int(input("Masukan Beberapa perulangan : "))
while n == n:
    break
for i in range(n):
    bil = random() % 0.5
    print("Perulangan ke : ", bil)
````
2. Hasil Run

![2](https://user-images.githubusercontent.com/115678251/200263284-cfeeaa5e-1fcf-4deb-b0dc-b86c26be2d7b.png)



# MODUL PRAKTIKUM 2 DAN 3

## Labpy02 dan Labpy03

### Labpy02
• Buat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya. Gunakan statement if.

Langkah - langkah
1. Buatlah flowchart dari mencari angka terbesar dari 3 bilangan seperti gambar dibawah ini

![Flowchart program mencari angka terbesar](https://user-images.githubusercontent.com/115678171/200159462-6b7e6bcb-8a43-4d48-a4c4-5bf8bda85a42.png)

2. Buatlah program codenya seperti gambar dibawah ini

![Mencari angka terbesar dari 3 bilangan ](https://user-images.githubusercontent.com/115678171/200159489-cf95f820-11ad-4366-a852-11da99dcfb2c.png)
```
a, b, c = (
    int(input('Masukkan nilai a: ')),
    int(input('Masukkan nilai b: ')),
    int(input('Masukkan nilai c: '))
)
if a > b and a > c:
    print('A yang terbesar')
elif b > a and b > c:
    print('B yang terbesar')
else:
    print('C yang terbesar')
````
3. Hasil dari Run

![Run Mencari angka terbesar dari 3 bilangan](https://user-images.githubusercontent.com/115678171/200159535-dce4f301-3d18-433f-9af9-170e57869329.png)

## Labpy03

### Latihan 1

Flowchart dari latihan 1

![Floawchart lat 1 labpy03](https://user-images.githubusercontent.com/115678171/200159707-ccb1abdb-be69-4849-96c8-6c02c439d199.png)

### Algoritma dari latihan 1
Menampilkan n bilangan acak yang lebih kecil dari 0,5, nilai n diisi pada saat runtime.

1.Memasukan/ import fungsi RANDOM terlebih dahulu

2.Deklarasi integer , masukkan jumlah n :

3.Memasukan deskripsi kombinasi for untuk menyelesaikannya.

4.Memasukan nilai jumlah (n) : 5

5.Mencetak data ke 1 sampai 5 dengan hasil nilai kurang dari 0,5.

6.Selesai

Langkah - langkah

1. Buat program caodenya seperti gambar dibawah ini 

![1](https://user-images.githubusercontent.com/115678251/200264870-5dc0b8c2-e72b-4bf1-bf19-53d64c7beec1.png)

```
print("bilangan acak yang lebih kecil dari o.5")
import random

n = int(input("masukan nilai:"))
a = 0
for c in range(n):
    a += 1
    b = random.uniform(.0, .5)
    print("data ke:", a, "==>", b)

print("selesai")
````
2. Hasil Run 

![2](https://user-images.githubusercontent.com/115678251/200264955-63a34f76-0231-46e0-be99-ebb77666fa11.png)


### Latihan 2

Flowchart dari latihan 2

![Flowchart lat 2 labpy03](https://user-images.githubusercontent.com/115678171/200159970-42dd1c12-2af8-416d-b808-822ed3c3c7fc.png)

### Algoritma latihan 2

Membuat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan.Masukkan angka 0 untuk berhenti

1.Mulai

2.Mencetak "latihan 2"

3.Mencetak "menampilkan bilangan, berhenti ketika bilangan 0, menampilkan bilangan terbesar"

4.integer max = 0

5.Menggunakan fungsi perulangan while true, hingga menampilkan perulangan sampai batas tertentu.

6.Memasukan bilangan integer pada "a"

7.Menggunakan fungsi if jika max kurang dari nilai a, maka max sama dengan a

8.Mengunakan fungsi if jika nilai a adalah 0 maka fungsi break artinya perulangan berhenti jika menulis nilai 0.

9.Mencetak nilai paling terbesarv setelah break, sehingga menampilkan nilai terbesar diantara bilangan tersebut dalam perulangan.

10.Selesai

Langkah - langkah

1. Buatlah program code seperti gambar dibawah ini


![1](https://user-images.githubusercontent.com/115678251/200265495-b6aa6a28-9f47-4f4e-897e-22c6f3df02a5.png)

```
print("menampilkan bilangan, berhenti ketika bilangan 0, dan menampilkan bilangan terbesar")

max = 0
while True:
    angka = int(input("masukan bilangan : "))
    if max < angka:
        max = angka
    if angka == 0:
        break
print("bilangan terbesarnya adalah = ", max)
print("======selesai======")
````
2. Hasil Run

![2](https://user-images.githubusercontent.com/115678251/200265553-2b46ab02-22b4-4347-8018-4744108b6e7c.png)


### Program 1

Flowchart dari program 1

![Flowchart Program 1](https://user-images.githubusercontent.com/115678171/200160200-2f3db728-7d3d-48c0-b21a-b8d3bf11438b.png)

### Algoritma dari program 1

1.Mulai

2.Mencetak latihan1

3.Mencetak "Program menghitung laba dengan modal awal 100 juta"

4.Membuat Note

5.Mencetak Bulan pertama dan kedua = 0%

6.Mencetak bulan ke 3 = 1%

7.Mencetak bulan ke 5 = 5%

8.Mencetak bulan ke 8 = 2%

9.integer a = 100.000.000( modal awal)

10.Menggunakan fungsi looping for pada nilai x 1-9 untuk menampilkan bulan 1 sampai bulan 8.

11.Menggunakan fungsi if, untuk menghitung laba bulan 1 sampai 8

12.bulan pertama dan kedua laba adalah 0

13.bulan ke 3 dan ke 4 mendapat laba 1% sehingga modal di kali 1% = keuntungan

14.bulan ke 5 mendapatkan laba 5%, sehingga modal dikali 5% = keuntungan

15.Bulan ke 8 mmendapatkan laba 2% sehingga keuntungan menurun dari bulan sebelumnya, modal dikali 2% = keuntungan.

16.Menghitung jumlah total laba dengan menjumlah keuntungan dari bulan ke 1 sampai bulan 8, hasilnya adalah total keuntungan yang didapat.

17.Selesai

Langkah - langkah

1. Buatlah program codenya seperti gambar dibawah ini

![Program 1](https://user-images.githubusercontent.com/115678171/200160306-fc80e487-e655-4d7d-a633-c54acaaeb641.png)
```
x = 100000000
sum = 0
y = 0
lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]
print("modal awal seorang pengusaha :', x")
for i in lb:
    sum = sum + i
    y += 1
    print("#laba bulan ke - ", y, "sebesar :", i)

    print("  TOTAL LABA YANG DIDAPAT ADALAH :", sum)
````
2. Hasil Run

![Run Program 1](https://user-images.githubusercontent.com/115678171/200160346-15ada2ee-a65f-480e-b36f-63d3a5804d57.png)

Sekian penjelasan dari saya Terima Kasih 



