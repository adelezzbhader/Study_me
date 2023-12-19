## Examples c++

```c++
#include <iostream>
#include<cmath>
using namespace std;

int main()
{
    /*
    char n;
    cout<<"enter char"<<endl;
    cin >> n ;
    int up , le ;
    up = (n == 'A' || n == 'E' || n == 'I' ||n == 'O' ||n == 'U' );
    le = (n == 'a' || n == 'e' || n == 'i' ||n == 'o' ||n == 'u' );
    if (up || le)
    {
        cout << "vowel"<<endl;
    }
    else
        cout << "not vowel"<<endl;

---------------------------------------------------------------------------------
    string  = "Adel" ;
    cout << str.length();

    int x ,ctr=0;
    cout << "enter the number :";
    cin >> x ;
    for (int i =1;i <=x;i++)
    {
        if (x%i==0)
        {
            ctr++;
        }
    }
    if (ctr==2)
    {
        cout <<"prime number ";
    }
    else
    {
        cout <<"not prime number ";
    }
-------------------------------------------------------------------------

    int x ,sum=0,sum2;
    cout << "enter the number :";
    cin >> x ;
    for (int i =1;i <=x;i++)
    {
        sum2 =0;
        for (int j =1;j <=i;j++)
        {
            sum+=j;
            sum2+=j;
            cout<<j;
            if (j<i)
            {
                cout<<" + ";
            }
        }
        cout<<" = "<<sum2 <<endl;
    }
    cout<<"the sum is : "<<sum ;


-------------------------------------------------------------------------------------------



    int num ,num1,num2,n ,sum,n1;
    cout<<"enter number"<<endl;
    cin >> num ;
    num1=num/100;
    n = (num%100);
    num2 = n/10 ;
    n1 = num%10;
    sum = n1+num1+num2;
    cout<<sum;
--------------------------------------------------------------------------

    int x ,a;
    float sum=0.0;
    cout << "enter the number :";
    cin >> x ;
    for (float i =1;i <=x;i++)
    {

        if(i<x)
        {
        cout<<"1/ "<<i<<" + " ;
        sum += 1/i ;
        }
        if (i==x)
        {
        cout<<"1/ "<<i;
        sum += 1/i ;
        }

    }
    cout<<endl;
    cout<< "the sum is "<<sum;

------------------------------------------------------------------


    int x ,sum=0;
    cout << "enter the number :";
    cin >> x ;
    for (int i =1;i <=x;i++)
    {
        for (int j =1;j <=i;j++)
        {
            cout<<i;
        }
    cout<<endl;
    }

-------------------------------------------------------------------

    int x , y , num=1;
    cout << "enter the base :";
    cin >> x ;
    cout << "enter the exponent :";
    cin >> y ;
    for (int i =1;i <=y;i++)
    {
        num *=x;
    }
    cout <<x<<" ^ "<<y<<" = "<<num ;

--------------------------------------------------------------------------

    int x ;
    cout << "enter the base :";
    cin >> x ;
    for (int i =1;i <=x;i++)
    {
        if (x % i ==0)
            cout<<i<<" ";
    }
    cout <<endl;

---------------------------------------------------------------------------------
   // this is external code .
    int number , x ,sum = 0;;
    cout << "enter the number :";
    cin >> number ;
    while (number > 0) {
        x = number % 10;
        sum += x;
        number /= 10;
    }

    cout << "sum = " << sum <<endl;
---------------------------------------------------------------------------------------------


    int numbers[] = {5, 2, 9, 1, 7};
    int size = sizeof(numbers) / sizeof(numbers[0]);

    int maxNumber = numbers[0];

    for (int i = 1; i < size; i++) {
        if (numbers[i] > maxNumber) {
            maxNumber = numbers[i];
        }
    }

    cout << "max is : " << maxNumber << endl;
---------------------------------------------------------------------------------------------------
*/


    
    return 0;
}

```

