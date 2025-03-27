#include <iostream>
using namespace std;

double add(double a, double b) {
    return a + b;
}

double subtract(double a, double b) {
    return a - b;
}

double multiply(double a, double b) {
    return a * b;
}

double divide(double a, double b) {
    if (b == 0) {
   
        cout << "error: division by zero!" << endl;
        return 0;
    } 
    return a / b;
}

int main() {
    double num1, num2;
    char operation;
    
    cout << "enter first number: ";
    cin >> num1;
    
    cout << "enter an operator (+, -, *, /): ";
    cin >> operation;
    
    cout << "enter second number: ";
    cin >> num2;
    
    switch (operation) {
        case '+':
        cout << "result: " << add(num1, num2) << endl;
        break;
        case '-':
        cout << "result: " << subtract(num1, num2) << endl;
        break;
        case '*':
        cout << "result: " << multiply(num1, num2) << endl;
        break;
        case '/':
        cout << "result: " << divide(num1, num2) << endl;
        break;
        default:
        cout << "error: invalid operator!" << endl;
    }
    return 0;
}
