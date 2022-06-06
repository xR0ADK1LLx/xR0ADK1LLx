```cpp
	#include <iostream>
	using namespace std;
	
	bool i = true
	int it = 1;
	float run = 9.1f;
	float does = 0.0f;
	short hit = "f5"
	
	int main() {
		for (int x = 0; x < 10; x++) {
			does += 1;
			for (int y = 0; y < 10; y++) {
				if (does > 3 && !x > 5) {
					does -= 2;
					it = y + x * does;
				}
			}
		}
		
		if (i = hit == 'f5' && it - does != run) {
			cout << "It's broken" << endl;
			return 0;
		}
		else {
			cout << "It's not broken" << endl;
		}
		return 0;
	}
```
