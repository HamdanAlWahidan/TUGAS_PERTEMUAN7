### NAMA: HAMDAN AL WAHIDAN
### KELAS: TI. 20. A. 1
### NIM: 312010114

_________________________________________________________________________________

Jadi pada pertemuan ini saya diberikan beberapa tugas oleh dosen saya yaitu diantaranya:

## TUGAS PRAKTIKUM LAB3 (LATIHAN 1)

![Latihan 1](https://github.com/HamdanAlWahidan/TUGAS_PERTEMUAN7/blob/main/Pertemuan7/latihan1.png) <br>

Pada tugas pertama, saya diminta untuk membuat sebuah program pengulangan bertingkat yang nantinya akan menghasilkan output seperti gambat diatas.
Untuk bisa dapat menghasilkan output tersebut maka saya memasukan syntax:

```
for row in range(0, 10):
    for col in range(0, 10):
        num = row + col
        if num < 10:
            empty = "  "
        else:
            if num < 100:
                empty  = " "
        print(empty, num, end = '')
    print()
```

Jika sudah memasukan semua syntax diatas dan telah di run, maka kamu akan mendapatkan tampilan seperti gambar yang ada dibawah ini.

![Foto Lat1](https://github.com/HamdanAlWahidan/TUGAS_PERTEMUAN7/blob/main/Lab3/Lab3.1.png) <br>

## TUGAS PRAKTIKUM LAB3 (LATIHAN 2)

![Latihan 2](https://github.com/HamdanAlWahidan/TUGAS_PERTEMUAN7/blob/main/Pertemuan7/latihan2.png) <br>

Di tugas ke dua, saya diminta untuk mencari nilai acak yang bernominal dibawah 0,5. Maka saya memasukan syntax:
```
from random import seed
from random import gauss

seed = int(input("Masukan Nilai N: "))

for i in range(seed):
    value = gauss(0,5)
    print ("Data ke ", i, ":", value)
```

Jika sudah memasukan semua syntax diatas dan telah di run, maka kamu akan mendapatkan tampilan seperti gambar yang ada dibawah ini

![Foto Lat2](https://github.com/HamdanAlWahidan/TUGAS_PERTEMUAN7/blob/main/Lab3/Lab3.png) <br>

___________________________________________________________________________________________________
