#include <iostream>
using namespace std;

class Distance {
    int meters, centimeters;

public:
    Distance(int m, int c) {
        meters = m;
        centimeters = c;
    }

    Distance operator+(Distance d) {
        int totalCm = centimeters + d.centimeters;
        int totalM = meters + d.meters + totalCm / 100;
        totalCm = totalCm % 100;

        return Distance(totalM, totalCm);
    }

    void display() {
        cout << meters << " meters " << centimeters << " centimeters\n";
    }
};

int main() {
    Distance d1(5, 70);
    Distance d2(3, 50);

    Distance d3 = d1 + d2;

    d3.display();

    return 0;
}
