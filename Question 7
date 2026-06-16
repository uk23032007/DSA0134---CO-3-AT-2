#include <iostream>
#include <fstream>
using namespace std;

class FileHandler {
    ofstream file;

public:
    FileHandler() {
        file.open("sample.txt");
        cout << "File opened\n";
    }

    void writeData() {
        file << "This is file handling using constructor and destructor.";
    }

    ~FileHandler() {
        file.close();
        cout << "File closed\n";
    }
};

int main() {
    FileHandler f;
    f.writeData();

    return 0;
}
