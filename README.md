#include <iostream.h>

void main() {
  int n,reversed = 0;

  cout << "Enter a number: ";
  cin >> n;

  while (n != 0) {
   int digit = n % 10;    //Get the last digit
     reversed = reversed * 10 + digit; // Add it to reversed number   n = n / 10;             // Remove the last digit
  }

  cout << "Reversed number = " << reversed << endl;
}
