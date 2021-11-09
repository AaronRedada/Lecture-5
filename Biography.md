#include <iostream>
#include <string>
using namespace std;

int main()
{
    string name, age, hometown;

    cout << "Please input your name:\n";
    cin >> name;
    cout << "\nPlease enter your age \n";
    cin >> age;
    cout << "\nPlease enter your hometown \n";
    cin >> hometown;

    cout << "\nHere is your information:\n";
    cout << "\nName: " << name << "\n";
    cout << "Age: " << age << "\n";
    cout << "Hometown:" << hometown << "\n";

    system("pause>0");
}
