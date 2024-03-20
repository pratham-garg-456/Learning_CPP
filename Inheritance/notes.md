# Inheritance

One class(derived) inherits from another class(Base).

syntax:

``` C++
#include <iostream>

using namespace std;

class Base{
    int datamember;
public:
    void memberFunction(){
      cout << " do something" <<endl; 
    }
};

class derived(): public Base{
    int dataMember;
public:
    void memberFunction(){
      cout << "do something additional"<< endl;
    }
};

```
