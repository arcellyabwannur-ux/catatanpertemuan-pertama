# catatanpertemuan-pertama
//Header
#include <iostream>
#include <string>
#include <cstdlib>
using namespace std;

//Main program
int main() {
   system ("cls"); // Clear the console screen
   string nama;
   int umur;

   //cout << "Masukkan nama Anda: ";
   //getline biar bisa input nama dengan spasi
   //getline(cin, nama);
   cout << "Nama : " << endl;
   getline(cin, nama);

   cout << "Umur : " << endl;
   cin >> umur;
   cout << "Nama Anda adalah " << nama << " dan umur Anda adalah " << umur << " tahun." << endl;
   return 0;
}
