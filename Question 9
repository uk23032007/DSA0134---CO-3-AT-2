#include <iostream>
#include <cstring>
using namespace std;

class Student {
    char *name;
    int marks;

public:
    Student(const char *n, int m) {
        name = new char[strlen(n) + 1];
        strcpy(name, n);
        marks = m;
    }

    Student(const Student &s) {
        name = new char[strlen(s.name) + 1];
        strcpy(name, s.name);
        marks = s.marks;
    }

    void modify(const char *n, int m) {
        strcpy(name, n);
        marks = m;
    }

    void display() {
        cout << "Name: " << name << ", Marks: " << marks << endl;
    }

    ~Student() {
        delete[] name;
    }
};

int main() {
    Student s1("David", 90);
    Student s2(s1);

    s2.modify("Hari", 95);

    s1.display();
    s2.display();

    return 0;
}
