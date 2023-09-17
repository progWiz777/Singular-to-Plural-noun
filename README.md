// Singular-to-Plural-noun 

// this is my first ever project

//programmer's name: Dhruv Ozarkar
//collage: ASSC Surat
//date: 17th sept 2023


//let's get started

#include <iostream>

using namespace std;

int main() {
    string noun;
    cout    << "enter a noun to get plural form of that noun: " << endl;
    getline(cin,noun);
    int pl;
    string Pn = noun+"a";
    pl = Pn.length();
    Pn[pl-1]= 's';
    cout << Pn <<endl;
    return 0;
}
