# 2.konversi-waktu
#include&lt;iostream>
using namespace std; 
int main() {     
int hari,jam,menit,detik,sisa1,sisa2,sisa3;      
cout&lt;&lt;"Masukan Jumlah Detik :";     cin>>detik;      
hari= detik/86400;    
sisa1= detik-(hari*86400);    
jam= sisa1/3600;    
sisa2= sisa1-(jam*3600);  
menit= sisa2/60;    
sisa3= sisa2-(menit*60);   
detik=sisa3;      cout&lt;&lt;hari&lt;&lt;"Hari "&lt;&lt;jam&lt;&lt;"Jam "&lt;&lt;menit&lt;&lt;"Menit "&lt;&lt;detik&lt;&lt;"Detik ";    
return 0;     }
