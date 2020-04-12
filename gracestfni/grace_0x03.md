1. Menurut saya, penggunaan deklarasi dinamis lebih baik dari deklarasi statis karena ukuran array 
   pada deklarasi statis ditentukan langsung pada kode program, sedangkan deklarasi dinamis kita dapat 
   menentukan ukuran array nya pada saat program berjalan.

2. 

       '#include <stdio.h>'
       '#include <stdlib.h>'
       'int main ()'  
       '{'
        'int i;'
        'char nama[6]={'G','R','A','C','E','\0'};'
        'for(i=0;i<=5;i++)'
        '{'
	      'printf("%c", nama[i]);'
        '}'
        'return 0;'
        '}'
    
3. 'Ndak paham'

4.

        '#include <stdio.h>'
        '#include <stdlib.h>'
        
	'int main()'
        '{'
        'int i,j;'
        'int baris=2;'
	'int kolom=3;'
	'int matrA [10][10];'
	'int matrB [10][10];'
        'int hasil [10][10];'
	
	'printf("Isi array Matriks A :\n");'
	'for (i = 0 ; i < baris; i++)'
        'for (j = 0 ; j < kolom; j++)'
        '{'
         'scanf("%d", &matrA [i][j]);'
        '}'
	 
	
	'printf("Isi array Matriks B :\n");'
	'for (i = 0 ; i < baris; i++)'
        'for (j = 0 ; j < kolom; j++)'
	'{'
          'scanf("%d", &matrB [i][j]);'
        '}'
	
	
	'printf("Hasil penjumlahan Matriks A dan Matriks B : \n");'
        'for (i = 0; i < baris; i++)'
        '{'
        'for (j = 0; j < kolom; j++)'
        '{'
            'hasil [i] [j] = matrA [i] [j] + matrB [i] [j];'
            'printf("%d", hasil [i] [j]);'
        '}'
	
        'printf("\n");'
	'}'
	
	
	'return 0;'
        '}'
