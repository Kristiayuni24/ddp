#include <iostream>

using namespace std;
int main(){
	   
	   float jumlah;
	   float hargapembelian;
	   float hargasaatini;
	   
	   //input
	   cout<<("(-------+++++++++Program Menentukan keuntungan/kerugian harga bitcoin++++++++--------)")<<endl;
	   
	   cout<<"masukan jumlah : "; cin>>jumlah;
	   cout<<"masukan hargapembelian : "; cin>>hargapembelian;
	   cout<<"masukan hargasaatini : "; cin>>hargasaatini;
	   
	   //output
	   cout<<("(-------++++++++Hasil dari program penentuan keuntungan/kerugian harga bitcoin+++++++------)")<<endl;
	   
	   cout<<"kenaikan/penurunan\t : " <<" "<<(hargasaatini - hargapembelian)/hargapembelian*100 <<"%\n" <<endl;
	   cout<<"keuntungan/kerugian\t : " <<(hargasaatini - hargapembelian)/1000000*0.5 <<" "<<"juta\n" <<endl;
	   
	   cout<<("(++++++++++++++++++++++++++++++++ Program Telah Selesai+++++++++++++++++++++++++++++++++++++++)") <<endl;
	   return 0;
}
