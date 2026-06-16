#include <iostream>
using namespace std;

class Mobile {
    string brand;
    float price;

public:
    Mobile() {
        brand = "Unknown";
        price = 0;
        cout << "Default Constructor called\n";
    }

    Mobile(string b, float p) {
        brand = b;
        price = p;
        cout << "Parameterized Constructor called\n";
    }

    Mobile(const Mobile &m) {
        brand = m.brand;
        price = m.price;
        cout << "Copy Constructor called\n";
    }

    void display() {
        cout << "Brand: " << brand << endl;
        cout << "Price: " << price << endl;
    }
};

int main() {
    Mobile m1;
    Mobile m2("Samsung", 25000);
    Mobile m3(m2);

    m1.display();
    m2.display();
    m3.display();

    return 0;
}
