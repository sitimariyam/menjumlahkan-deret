# menjumlahkan-


     #include <iostream>
    #include <conio.h>
    using namespace std;
    int main()
    {
    int a,b,c,n;
    a=0;
    b=1;
    cout<<"Menampilkan deret bilangan fibonacci : \n";
    cout<<"\nInput batas deret : "; cin>> n;
    cout<<"        "<<a<<"   "<<b<<"   ";
    n=(n-2);
    for (c=1;c<=n;c++){
    if (c%2==1){
        a=a+b;
        cout<<a<<"   ";
    }else{
    b=b+a;
    cout<<b<<"";
    }
    }
    }
