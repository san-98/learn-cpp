# learn-cpp

cpp is good OOP for beginners

``` cpp
#include <iostream>
using namespace std;

int main()
{
    int a = 5, b = 10, temp;

    cout << "Before swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    temp = a;
    a = b;
    b = temp;

    cout << "\nAfter swapping." << endl;
    cout << "a = " << a << ", b = " << b << endl;

    return 0;
}
```

``` cpp
#include <iostream>
using namespace std;

int main()
{
    int a = 5;
    int b = 10;
    
    cout << a+b << endl;
    return 0;
}
```

``` cpp
#include<iostream>
using namespace std;
int main() {
   int num = 20, i;
   cout << "The factors of " << num << " are : ";
   for(i=1; i <= num; i++) {
      if (num % i == 0)
      cout << i << " ";
   }
   return 0;
}
```

``` cpp
#include<iostream>
using namespace std;
int main() {
    cout << "Hacktoberfest 2022";
   return 0;
}
```
