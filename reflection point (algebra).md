```cpp
#include <iostream>
using namespace std;

int main() {
	// finding p' (reflection point)
	int n;
	cin >> n;
	int px, py, qx, qy;
	while(n)
	while (cin >> px >> py >> qx >> qy) {
		//p'x - qx = qx - px	-> p'x = 2qx - px
		//p'y - qy = qy - py	-> p'y = 2qy - py
		cout << 2 * qx - px << ' ' << 2 * qy - py << endl;
	}
	return 0;
}
```
