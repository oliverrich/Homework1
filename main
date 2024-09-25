#include <iostream>
#include <string>

using namespace std;

void printBinary(int number) {
   
   if (number == 0) {
      cout << "Binary representation: 0" << endl;
      return;
   }

   string binary;

//string manip
   while (number > 0) {
      binary = to_string(number % 2) + binary;
      number /= 2;
   }


   cout << "Binary representation: " << binary << endl;
}

int main() {
   int number;

   cout << "Enter an integer: ";
   cin >> number;

   
   printBinary(number);
   return 0;
}
