#include <iostream>
using namespace std;

int main (){
    int nilai; 
    cout << "Masukkan nilai: ";
    cin >> nilai; 
    
    if (nilai >=90){
        cout << "Grade A\n";
    } else if (nilai >= 80){
        cout << "Grade B\n";
    } else if (nilai >= 70){
        cout << "Grade C\n";
    } else {
        cout << "Grade D\n";
    }
}
