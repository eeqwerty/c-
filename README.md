#include<iostream>
using namespace std;
int main()
{
int a, b, c;
cout << "Enter  numbers: ";
cin >> a >> b >> c;

cout << "Before swapping:\n";
cout << "a = " << a << "\n" ;
cout << "b = " << b << "\n" ;
cout << "c = " << c << "\n" ;

// SWAPPING A & C  
    a=a+c;
    c=a-c ;
    a=a-c;

// SWAPPING A & B     
    a=a+b;
    b=a-b;
    a=a-b;

cout << "After swapping:\n" ;
cout << "a = " << a << "\n" ;
cout << "b = " << b << "\n";
cout << "c = " << c << "\n";	
	
	return 0;
}
