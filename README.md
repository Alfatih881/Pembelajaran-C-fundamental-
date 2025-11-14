# Pembelajaran-C-fundamental-
Dasar-dasar C++ yang mencakup struktur program, operator, loop, fungsi, dan konsep OOP.
C++-Fundamental/
├─ 00-README.md
├─ 01-basics/
│  ├─ 01-syntax.md
│  ├─ 02-variables.cpp
│  └─ exercises.md
├─ 02-control-flow/
│  ├─ if_else.cpp
│  ├─ loops.cpp
│  └─ exercises.md
├─ 03-functions/
├─ 04-pointers-arrays/
├─ 05-oop/
└─ resources/
   └─ cheatsheet.md
   #include <iostream>
using namespace std;

int main() {
    int i = 1;
    // do-while memastikan blok dieksekusi minimal sekali
    do {
        cout << "Iterasi ke-" << i << endl;
        i++;
    } while (i <= 5);

    return 0;
}# compile
g++ -std=c++17 main.cpp -o main
# run
./main
