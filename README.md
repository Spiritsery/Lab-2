// Rajit Swarup
// Jonnathan Quijada
// Eric Oh
// Description: Hello World in C++
//============================================================
main
#include <iostream>
using namespace std;
int hello1Function(string name1);
int hello2Function(string name2);
int main()
{
string name1="Jonnathan Quijada";
hello1Function(name1);
string name2="Eric Oh";
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
https://forum.qt.io/topic/149758/macos-project-error-failed-to-parse-default-search-paths-from-compiler-output
