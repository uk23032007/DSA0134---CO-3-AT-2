#include <iostream>
using namespace std;

class Box {
    int volume;

public:
    Box(int v) {
        volume = v;
    }

    bool operator>(Box b) {
        return volume > b.volume;
    }

    void display() {
        cout << "Volume: " << volume << endl;
    }
};

int main() {
    Box b1(100);
    Box b2(150);

    if (b1 > b2)
        cout << "Box 1 is greater\n";
    else
        cout << "Box 2 is greater\n";

    return 0;
}
