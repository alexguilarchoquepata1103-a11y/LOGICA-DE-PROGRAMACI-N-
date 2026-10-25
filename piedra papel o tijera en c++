#include <iostream>
#include <cstdlib>
#include <ctime>
using namespace std;
int main() {
    srand(time(0));
    int eleccion;
    cout<<"SELECCIONE:"<<endl<<"(1) piedra"<<endl<<"(2) papel"<<endl<<"(3) tijera"<<endl;
    cin>>eleccion;
    
    int computadora;
    computadora = rand() % 3 + 1;
    cout<<"la eleccion de la computadora fue: "<<computadora<<endl;
    
    if(eleccion==computadora) {
        cout<<"empate!"<<endl;}
        else if ((eleccion==1 && computadora==3) || (eleccion==2 && computadora==1) || (eleccion==3 && computadora==2)) {
            cout<<"ganaste!"<<endl;
        }
        else {
        cout<<"la computadora gana";}
    
    return 0;
    
}