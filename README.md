# t-m-s-nguy-n-t-
tìm số nguyên tố
#include <iostream>
#include <math.h>
using namespace std;
bool khoi(int n){
 for ( int i=2;i<=sqrt(n);i++){
 if ( n % i == 0){
    return false;}

 }
 return true;

}
main (){
    cout <<" nhap so muon kiem tra"<<endl;
    int a;
    cin>>a;
for ( int i=0;i<=a;i++){
        if ( khoi(i)){
            cout<<i<<endl;
        }
}
return 0;
}
