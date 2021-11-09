#include <iostream>
using namespace std;

int main()
{
    double a, c, r;
    cout << "Please enter the Radius of the circle to know the Area and Circumference:\n";
    cin >> r;
    a = 3.14159265359 * (r * r);
    c = 2 * 3.14159265359 * r;

    cout << "\nANSWER\n";
    cout << "\nRadius: " << r << "\n";
    cout << "Area: " << a << "\n";
    cout << "Circumference: " << c << "\n";

    system("pause>0");
}
