#include <iostream>
using namespace std;

int main()
{
    double length, width, rectangle, triangle, square;

    cout << "To Calculate the Area of a Rectangle, Triangle and Square, please enter the following:\n";
    cout << "\nEnter the Length:\n";
    cin >> length;
    cout << "Enter the Width:\n";
    cin >> width;

    rectangle = length * width;
    triangle = (length * width) / 2;
    square = length * length;

    cout << "\nANSWER:\n";
    cout << "These are the Area of the following:\n";
    cout << "\nRectangle: " << rectangle << "\n";
    cout << "Triangle: " << triangle << "\n";
    cout << "Square: " << square << "\n";

    system("pause>0");
}                 
