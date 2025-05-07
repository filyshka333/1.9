#include <iostream> 
using namespace std; 
class Opa { 
 int chislo; 
public: 
 void res() 
 { 
  cin >> chislo; 
  cout << "вот какое число Вы ввели  " << chislo << endl; 
   
 } 
}; 
int main() 
{ 
 setlocale(LC_ALL, "Russian"); 
 Opa k; 
 k.res(); 
  
}
