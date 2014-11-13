starline
========
#include <iostream>
using namespace std;

void starline();

int main()
{
    starline();
    cout<<"Data type Range"<<endl;
    starline();    //call to function
    cout<<"char      -128 to 127"<<endl;
    cout<<"short     -32,768 to 32768"<<endl;
    cout<<"int       System dependent"<<endl;
    cout<<"long      -2,147,483,648 to 2,147,483,648"<<endl;
    starline();    //call to function
    return 0;
}

void starline()    //function declarator
{
    for (int j=0; j<45; j++) {
        cout<<'*';
        
    }
    cout<<endl;
}
