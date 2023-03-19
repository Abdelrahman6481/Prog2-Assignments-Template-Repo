//Abdelrahman Montaser
//20216481

#include <iostream>
using namespace std;

int main() {
    int x;
    cin >> x;
    
    int firstDigit = x / 1000;  // extract the first digit
    if (firstDigit % 2 == 0) {
        cout << "EVEN" << endl;
    } else {
        cout << "ODD" << endl;
    }
    
    return 0;
}
