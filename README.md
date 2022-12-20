# Ujian Akhir Semester 
Mata Kuliah 	      : Dasar Pemrograman 
Nama		      : Syifa Arifah Nurbayani
NIM		      :	1227050131
Jurusan		      :[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum

Matriks adalah sekumpulan bilangan yang disusun berdasarkan baris dan kolom, serta ditempatkan di dalam tanda kurung.Tanda kurungnya ini bisa berupa kurung biasa “( )” atau kurung siku “[ ]”. Suatu matriks diberi nama dengan huruf kapital, seperti A, B, C, dan seterusnya. 


## Source Code
#include <iostream>

using namespace std;
int main()
{
    int Matriks[4][4];
    int i,j,k, baris, kolom,brs,klm,m,n,o;

  		cout<<"Nama : Syifa Arifah Nurbayani"<<endl;
  		cout<<"NIM  : 1227050131"<<endl;
  		cout<<"Kelas: IF-C"<<endl<<endl;
  		
  		
      	cout<< "==========================================================================================================="<<endl;
        cout <<"| 1. PROGRAM ARRAY 2 DIMENSI JUMLAH BARIS,KOLOM, NILAI DI INPUTKAN DAN DIBALIK BARIS > KOLOM,KOLOM > BARIS |"<<endl;
        cout<< "==========================================================================================================="<<endl;
        cout << " Masukkan banyak baris : ";
        cin >> baris;
        cout << " Masukkan banyak kolom : ";
        cin >> kolom;
		
		cout<<endl;
  

    
    cout << " Matriks A ("<<baris<<"x"<<kolom<<")"<<endl;
    
    for (i = 0;i < baris; i++){
        for (j = 0;j < kolom;j++){
            cout << " Nilai ke- ["<<i<<","<<j<< "] = ";
            cin >> Matriks[i][j];
        }
    }cout <<endl;

    
    cout << " Matriks A ("<<baris<<"x"<<kolom<<")"<<endl<<endl;
    
    for (i = 0;i < baris;i++){
        for (j = 0; j < kolom;j++){
            cout <<"\t"<<Matriks[i][j];
        }
        cout <<endl<<endl;
    }
    
    cout<<endl;
    
    cout << " Matriks A Dibalik >> baris jadi kolom, kolom jadi baris ("<<kolom<<"x"<<baris<<")"<<endl<<endl;
    for (i = 0;i < kolom;i++){
        for (j = 0; j < baris;j++){
            cout <<"\t"<<Matriks[j][i];
        }
        cout <<endl<<endl;
    }
    
    cout<<endl;
    
    cout<< "========================================================================"<<endl;
    cout <<"| 2. PROGRAM ARRAY 2 DIMENSI NILAI YANG DI INPUTKAN HABIS DIBAGI 3,5,7 |"<<endl;
    cout<< "========================================================================"<<endl;
    
     	cout << " Masukkan banyak baris : ";
    	cin >> baris;
    	cout << " Masukkan banyak kolom : ";
        cin >> kolom;
		
		cout<<endl;
  

    
    cout << " Matriks A ("<<baris<<"x"<<kolom<<")"<<endl;
    
    for (i = 0;i < baris; i++){
        for (j = 0;j < kolom;j++){
            cout << " Nilai ke- ["<<i<<","<<j<< "] = ";
            cin >> Matriks[i][j];
            
        }
    }cout <<endl<<endl;

	cout << " Matriks A ("<<baris<<"x"<<kolom<<")"<<endl<<endl;
	for (i = 0;i < baris;i++){
        for (j = 0; j < kolom;j++){
        	
            cout <<"\t"<<Matriks[i][j];
            
        }
        cout <<endl<<endl;
    }
      cout<<endl<<endl;
      
      
    cout<<" Nilai Matriks A yang Habis Dibagi 3, 5 , 7 : "<<endl<<endl;
    for (i = 0;i < baris;i++){
        for (j = 0; j < kolom;j++){
        	if(Matriks[i][j]%3==0){
        		cout<<"\t"<<Matriks[i][j];
			}
			else if (Matriks[i][j]%5==0){
				cout<<"\t"<<Matriks[i][j];
			}
			else if (Matriks[i][j]%7==0){
				cout<<"\t"<<Matriks[i][j];
			}
			else {
			}
            
        }
        cout <<endl<<endl; 
    }
    
    return 0;
}
 
  
## Output
  
Nama : Syifa Arifah Nurbayani
NIM  : 1227050131
Kelas: IF-C

===========================================================================================================
| 1. PROGRAM ARRAY 2 DIMENSI JUMLAH BARIS,KOLOM, NILAI DI INPUTKAN DAN DIBALIK BARIS > KOLOM,KOLOM > BARIS |
===========================================================================================================
 Masukkan banyak baris : 2
 Masukkan banyak kolom : 3

 Matriks A (2x3)
 Nilai ke- [0,0] = 2
 Nilai ke- [0,1] = 9
 Nilai ke- [0,2] = 7
 Nilai ke- [1,0] = 5
 Nilai ke- [1,1] = 1
 Nilai ke- [1,2] = 3

 Matriks A (2x3)

        2       9       7

        5       1       3


 Matriks A Dibalik >> baris jadi kolom, kolom jadi baris (3x2)

        2       5

        9       1

        7       3


========================================================================
| 2. PROGRAM ARRAY 2 DIMENSI NILAI YANG DI INPUTKAN HABIS DIBAGI 3,5,7 |
========================================================================
 Masukkan banyak baris : 2
 Masukkan banyak kolom : 3

 Matriks A (2x3)
 Nilai ke- [0,0] = 14
 Nilai ke- [0,1] = 4
 Nilai ke- [0,2] = 2
 Nilai ke- [1,0] = 11
 Nilai ke- [1,1] = 25
 Nilai ke- [1,2] = 9


 Matriks A (2x3)

        14      4       2

        11      25      9



 Nilai Matriks A yang Habis Dibagi 3, 5 , 7 :

        14

        25      9

  
  
  
  
