#include <iostream>
using namespace std;

class Number {
    int value;

public:
    Number(int v) {
        value = v;
    }

    void operator-() {
        value = -value;
    }

    void display() {
        cout << "Value: " << value << endl;
    }
};

int main() {
    Number n1(10);

    n1.display();

    -n1;

    n1.display();

    return 0;
}
