#include <iostream>
using namespace std;

class Test {
public:
    Test() {
        cout << "Constructor called\n";
    }

    ~Test() {
        cout << "Destructor called\n";
    }
};

int main() {
    cout << "Main starts\n";

    Test t1;

    {
        Test t2;
        {
            Test t3;
        }
    }

    cout << "Main ends\n";

    return 0;
}
