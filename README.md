// leer-imprimir-matrices
#include <bits/stdc++.h>
using namespace std;

int leer(int a[][7],int b,int c){
for(int i=0;i<b;i++){
for(int j=0;j<c;j++){
    a[i][j]=rand()%(9)+1;}}
}
int imprimir(int a[][7],int b,int c){
for(int i=0;i<b;i++){cout<<endl;
for(int j=0;j<c;j++){
    cout<<setw(3)<<a[i][j]<<setw(5);
    }}
}

