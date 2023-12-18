```c++
#include<iostream>
using namespace std ;
int main()
{
    //this is example for Creating a Calculator
    int x,y ;
    char op ;
    cout << "enter x :" <<endl;
    cin >>x ;
    cout << "enter y :" <<endl;
    cin >>y ;
    cout <<"enter the operation :"<<endl;
    cin >> op ;
    if (op =='+')
    {
        cout<<x+y ;
    }
    else if (op =='-')
    {
        cout<<x-y ;
    }
    else if (op =='*')
    {
        cout<<x*y ;
    }
    else if (op =='/')
    {
        cout<<x/y ;
    }

    int num ;
    cout << "enter number :" <<endl;
    cin >>num ;
    if (num != 0)
    {
        if (num % 2 == 0)
        {
            cout<<"even number "<<endl;
        }
        else if (num % 2 != 0)
        {
            cout<<"odd number "<<endl;
        }
    }
    else
        cout<<"another number "<<endl;
        

    return 0;
}
```

```c++
#include <iostream>
#include<cmath>
using namespace std;
int main()
{
    int x ,ctr=0;
    cout <<"enter the number :" <<endl;
    cin >> x ;
    for (int i =1 ; i <=x ; i++)
     {
         if (x % i ==0)
         {
            ctr++;
         }

     }
    if (ctr == 2)
     {
        cout<<"prime number "<<endl;
     }
    else
     {
        cout<<" not prime number "<<endl;
     }



    return 0;
}

```

```c++
#include <iostream>
#include<cmath>
using namespace std;
int main()
{
    int x ,ctr=0;
    cout <<"enter the number :" <<endl;
    cin >> x ;
    for (int i =1 ; i <=x ; i++)
    {
        for (int j=1 ; j <=x ;j++)
    {
        cout <<"# ";
    }
        cout<<"\n";

    }
    return 0;
}

```

```c++
#include <iostream>
#include<cmath>
using namespace std;
int main()
{
    int x ,ctr=0;
    cout <<"enter the number :" <<endl;
    cin >> x ;
    for (int i =1 ; i <=x ; i++)
    {
        for (int j=1 ; j <=i ;j++)
    {
        cout << " " <<i;
    }
        cout<<"\n";

    }
    return 0;
}

```

```c++
#include <iostream>
#include<cmath>
using namespace std;
int main()
{
    int x ,y,t;
    cout <<"enter the number :" <<endl;
    cin >> x ;
    cout <<"enter the number :" <<endl;
    cin >> y;
    t = pow(x,y);
    cout <<t ;
    return 0;
}

```

```c++
#include <iostream>
#include<cmath>
using namespace std;
int main()
{
    int x ,ctr=0;
    cout <<"enter the number :" <<endl;
    cin >> x ;
    for (int i =1 ; i <=x ; i++)
    {
        if (x %i == 0)
        {
            cout<< " "<<i ;
        }


    }
    return 0;
}

```

## there are some of examples of sheet 4 

```c++
#include <iostream>
#include<cmath>
using namespace std;

int power(int b ,int o)
{
    int res =1 ;
    res = pow(b,o);
    return res ;
}
int main()
{
    int x ;
    x =power(2,3) ;
    cout <<x<<endl;

    return 0;
}

```

```c++
#include <iostream>
#include<cmath>
using namespace std;

void name(string name)
{
   cout <<"hello "<< name <<endl;
}
int main()
{
    cout <<"enter your name :" ;
    string n ;
    cin >> n;
    name(n);


    return 0;
}

```

