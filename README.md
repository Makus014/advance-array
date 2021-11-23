# advance-array




//input 5 integer
#include <iostream>
using namespace std;

int main() {

	int integer[5];

	cout << "type any number " << endl;

	for (int i = 0; i < 5; i++) {
		cin >> integer[i];

			while (cin.fail()) {
				cout << "Invalid Command! " << endl;
				cin.clear();
				cin.ignore(1000, '\n');
				cin >> integer[i];

			}	
	}
	cout << "The output is " << endl;
	for (auto integ : integer) {
		cout << integ << endl;
	}


	return 0;
}
  
  
  
  
  
  
