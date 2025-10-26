#include <iostream>
#include <string>
#include <algorithm>
using namespace std;

int main() {
    int n;
    cin >> n;

    string bin = "";
    while (n) {
        bin.push_back((n % 2 == 0) ? '0' : '1');
        n >>= 1;
    }

    reverse(bin.begin(), bin.end());
    cout << bin << "\n";

    return 0;
}
