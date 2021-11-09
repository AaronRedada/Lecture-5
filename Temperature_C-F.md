#include <iostream>
using namespace std;

int main()
{
    double x;
    double y;
    cout << "Please enter the temperature in Celsius you wish to convet to Farenheit:\n";
    cin >> x;

    y = (x * 1.8) + 32;

    cout << "\nANSWER:\n";
    cout << x << " degrees Celsius converts to " << y << " degrees Farenheit.";

    system("pause>0");


}
