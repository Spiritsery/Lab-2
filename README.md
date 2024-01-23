// Rajit Swarup
// Description: Hello World in C++
//============================================================
main
#include <iostream>
using namespace std;
int hello1Function(string name1);
int hello2Function(string name2);
int main()
{
string name1="your name1";
hello1Function(name1);
string name2="your name2";
hello2Function(name2);
return 0;
}
hello1Function
/*
* hello1Function.cpp
*
*/
#include <iostream>
using namespace std;
int hello1Function(string name1)
{
cout << "hello World " << name1 << endl;
return 0;
}
Lab 2
hello1Function
/*
* hello2Function.cpp
*
*/
#include <iostream>
using namespace std;
int hello2Function(string name2)
{
cout << "hello World " << name2 << endl;
return 0;
}
Part 2
Put at least 5 doxygen commands within the inherit2 example. Generate the
corresponding documentation. Install graphviz. Work with a partner. Illustrate the
results.
//******************************************************************
****
//inherit2.h header file for the PersonType class
#ifndef H_PersonType
#define H_PersonType
#include <string>
using namespace std;
class personType
{
