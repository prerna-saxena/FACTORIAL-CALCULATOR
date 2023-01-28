# FACTORIAL-CALCULATOR



// Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;

int factorial(int n) {
    if(n==0||n==1)
       return 1;
    
    return n* factorial(n-1);
}

//DRIVER CODE
int main(){
    int num=10;
        cout << "Factorial of "
         << num << " is " << factorial(num) << endl;

    return 0;
}
