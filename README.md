# calculator-C
#include <stdio.h>

int main(){
	int a, b, hasil, menu;
	float c, d, hasilbagi;
	printf("==================================\n");
	printf("Program Kalkulator Sederhana");
	printf("==================================\n\n");
	printf("\tMenu : \n");
	printf("\t1. Penjumlahan\n");
	printf("\t2. Penguarangan\n");
	printf("\t3. Perkalian\n");
	printf("\t4. Pembagian\n");
	printf("Pilih menu : ");
	scanf("%d", &menu);
	printf("-----------------------------------\n");
	switch(menu){
		case 1:
			printf("\n1. Penjumlahan : \n");
			printf("Masukkan bilangan pertama : ");
			scanf("%d", &a);
			printf("Masukkan bilangan kedua : ");
			scanf("%d", &b);
			hasil = a + b;
			printf("-------------------------------- +\n");
			printf("Hasil :\t\t\t	%d\n", hasil);
			break;
		case 2:
			printf("\n2. Pengurangan : \n");
			printf("Masukkan bilangan pertama : ");
			scanf("%d", &a);
			printf("Masukkan bilangan kedua : ");
			scanf("%d", &b);
			hasil = a - b;
			printf("-------------------------------- -\n");
			printf("Hasil :\t\t\t	%d\n", hasil);
			break;
		case 3:
			printf("\n3. Perkalian : \n");
			printf("Masukkan bilangan pertama : ");
			scanf("%d", &a);
			printf("Masukkan bilangan kedua : ");
			scanf("%d", &b);
			hasil = a * b;
			printf("-------------------------------- x\n");
			printf("Hasil :\t\t\t	%d\n", hasil);
			break;
		case 4:
			printf("\n4. Pembagian : \n");
			printf("Masukkan bilangan pertama : ");
			scanf("%f", &c);
			printf("Masukkan bilangan kedua : ");
			scanf("%f", &d);
			hasilbagi = c / d;
			printf("-------------------------------- :\n");
			printf("Hasil :\t\t\t	%.2f\n", hasilbagi);
			break;
			default:
				printf("Anda salah memilih.");
				break;
	}
	return 0;
}
