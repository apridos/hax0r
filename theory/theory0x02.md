## Array

Array adalah sebuah variabel, tentu juga befungsi sebagai penampung data. Yang membedakan array dengan variabel biasa adalah, array memiliki kemampuan untuk menampung lebih dari satu nilai. Namun ada hal yang harus diperhatikan, yaitu array hanya dapat menampung **satu jenis** nilai.

### Deklarasi

#### Deklarasi dengan menentukan ukuran

##### a. Static declaration

Berdasarkan kata kunci *static*, **ukuran** array pada deklarasi ini ditentukan langsung melalui kode program.

```
int myArr1[10];
```
Array `myArr1` dapat menampung sampai dengan **10 bilangan bulat**. Situasi ini akan bertahan sampai kita mengubah ukurannya langsung di kode program.

#### b. Dynamic declaration

```
int i;
scanf("%d", &i);
int myArr2[i];
```

Perhatikan bahwa `myArr2` memiliki kemampuan untuk menyimpan bilangan bulat **sebanyak n**. Nilai `n` tidak ditentukan di dalam kode, melainkan ditentukan oleh pengguna ketika program berjalan. Sifat ini kemudian dapat kita korelasikan dengan kata **dinamis** (*dynamic*).

#### Deklarasi melalui inisialisasi

Selain dengan hanya menentukan ukuran terlebih dahulu, deklarasi array juga dapat dilakukan dengan mengisikannya dengan elemen-elemen.

```
char arr[] = {`H`, 'A', 'X', '0', 'R'};
```


#### Deklarasi kombinasi menentukan ukuran dan inisialisasi

Deklarasi di bawah ini juga merupakan bentuk yang valid,
```
char nama[4] = {'n', 'a', 'm', 'a'};
```

### Inisialisasi


Seperti nomor kamar di asrama, **indeks** adalah indentitas untuk ruangannya bukan untuk **orang-orang** di dalamnya.

|Index|0|1|2|3|4|5|
|---|---|---|---|---|---|---|
|Element | C | O | R | O | N | A |

Misalkan array di atas dideklarasikan seperti ini,

```
char penyakit[6];
```

Untuk mengisikan setiap elemennya, dapat dilakukan mulai dari ruang pertama dengan indeks **0**. 

```
penyakit[0] = 'C';
penyakit[1] = 'O';
penyakit[2] = 'R';
penyakit[3] = 'O';
penyakit[4] = 'N';
penyakit[5] = 'A';
```

## Array n dimensi (multidimensi)

Jenis array ini erat kaitannya dengan matriks.

```
int matriks[2][3];
```

Strukturnya akan terlihat seperti ini

| Indeks | 0 | 1 | 2 |
|---|---|---|---|
| 0 | 0,0 | 0,1 | 0,2 |
| 1 | 1,0 | 1,1 | 1,2 |




