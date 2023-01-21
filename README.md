# navratan#include <iostream>
using namespace std;

// function with one int parameter
void print(int x) {
    cout << "The value of x is: " << x << endl;
}

// function with one double parameter
void print(double x) {
    cout << "The value of x is: " << x << endl;
}

// function with two int parameters
void print(int x, int y) {
    cout << "The value of x is: " << x << endl;
    cout << "The value of y is: " << y << endl;
}

int main() {
    print(5); // calls the first function
    print(6.7); // calls the second function
    print(8, 9); // calls the third function
    return 0;
}
