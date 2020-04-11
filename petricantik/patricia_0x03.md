## *Patricia's*

#### 1. Alasan deklarasi dinamis lebih baik dari pada deklarasi statis
Berdasarkan pandangan saya, deklarasi dinamis lebih baik dari deklarasi statis karena deklarasi dinamis akan menampung tipe data yang kita inginkan, tidak berpatokan di dalam kode. Pengguna akan menentukan banyak yang akan ditampung sebuah array saat program berjalan.

#### 2. Berikut adalah sebuah array yang menampung nama depanku yaitu `Patricia` dengan menggunakan for loop. Pada code tersebut, x adalah jumlah nama depan yang akan ditampilkan.

```
//patricia cuteee

#include <stdio.h>

int main()
{
    char nama[8];

    for (int i = 0 ; i < 8 ; i++)
    {
        scanf("%s", &nama[i]);
    }
    
    for (int i = 0 ; i < 8 ; i++)
    {
        printf("%c", nama[i]);
    }

    return 0;
}
```

#### 4. Operasi dua matriks

```
//patricia cuteee

#include <stdio.h>

int main()
{
    int matrA [10] [10] , matrB [10] [10] , hasil [10] [10];
    int row = 2, col = 3;
    int i, j;

    printf("Masukkan elemen dari Matriks A :\n");
    for (i = 0 ; i < row ; i++)
        for (j = 0 ; j < col; j++){
            scanf("%d", &matrA [i] [j]);
            }

    printf("Masukkan elemen dari Matriks B :\n");
     for (i = 0 ; i < row ; i++)
        for (j = 0 ; j < col; j++){
            scanf("%d", &matrB [i] [j]);
            }

    printf("Hasil dari Matriks A dan Matriks B : \n");
    for (i = 0; i < row; i++)
    {
        for (j = 0; j < col; j++)
        {
            hasil [i] [j] = matrA [i] [j] + matrB [i] [j];
            printf("%d ", hasil [i] [j]);
        }
        printf("\n");
    }

    return 0;

}
```
> please share, comment, and suscribes, because suscribes is free.
***@patriciasibarani***
