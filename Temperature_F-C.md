#include <iostream>
using namespace std;

int main()
{
    double x;
    double y;
    cout << "Please enter the Farenheit you wish to convet to Celsius:\n";
    cin >> x;
    
    y = (x - 32) * 0.556;

    cout << "\nANSWER:\n";
    cout << x << " degrees Farenheit converts to " << y << " degrees Celsius";

    system("pause>0");

    
}
