#include <iostream>
using namespace std;

double add(double a, double b) { return a + b; }
double subtract(double a, double b) { return a - b; }
double multiply(double a, double b) { return a * b; }

double divide(double a, double b) {
    if (b == 0) {
        cout << "Error: Division by zero!" << endl;
        return 0;
    }
    return a / b;
}

int main() {
    double num1, num2;
    char operation;
    
    cout << "Enter first number: ";
    cin >> num1;
    
    cout << "Enter an operator (+, -, *, /): ";
    cin >> operation;
    
    cout << "Enter second number: ";
    cin >> num2;
    
    cout << "Result: ";
    switch (operation) {
        case '+': cout << add(num1, num2) << endl; break;
        case '-': cout << subtract(num1, num2) << endl; break;
        case '*': cout << multiply(num1, num2) << endl; break;
        case '/': cout << divide(num1, num2) << endl; break;
        default: cout << "Error: Invalid operator!" << endl;
    }
    
    return 0;
}
