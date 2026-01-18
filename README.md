ufuk sökmen okul no 2507020070 bilgisayar mühendisi
# MatematikFinalSoru-1
UFUK SÖKMEN 2507020070  bilgisayarmühendisi
[Matematik ödevi.cpp](https://github.com/user-attachments/files/24696201/Matematik.odevi.cpp)
#include <iostream>
#include<cmath>

using namespace std;

main(){
	int a,b,c,Diskriminant;
	setlocale (LC_ALL,"Turkish");
	cout<<"ax�+bx+c i�leminden a y� giriniz:";
	cin>>a;
	cout<<"ax�+bx+c i�leminden b y� giriniz:";
	cin>>b;
	cout<<"ax�+bx+c i�leminden c y� giriniz:";
	cin>>c;
	Diskriminant=(b*b)-(4*a*c);
	cout<<"Delta de�eri:"<<Diskriminant<<endl;
	if (Diskriminant<0){
		cout<<"Delta s�f�rdan k���k oldu�u i�in reel k�k yok.";
	}
	else if (Diskriminant=0){
		cout<<"Delta s�f�ra e�it oldu�u i�in �ift katl� k�k";
	}
	else{
		cout<<"Delta s�f�rdan b�y�k oldu�u i�in iki farkl� k�k� var";
	}
}
