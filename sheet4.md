## sheet 4

1-Write a program that calculates 6^5. Declare your own function to do this

```c++
#include <iostream>
#include<cmath>
using namespace std;

int num(int base , int component)
{
    int result =1 ;
    for (int i=0 ;i <component ; i++ ){
        res *=base ;
    }
    return result ;
}

int main()
{
    int x = num(6,5);
        cout<<"5 ^ 6 = "<<x <<endl;



    return 0;
}

```

2-Write a program that asks a name say hello. Use your own function that receives a string of characters (name) and prints on screen the hello message. 

```c++
#include <iostream>
#include<cmath>
using namespace std;
void say(string name){
    cout<<"hello "<<name<<endl;
}

int main()
{
    string n ;
    cout <<"enter your name "<<endl;
    cin>>n ;
    say(n);




    return 0;
}

```

3-Write a program that ask for two numbers, compare them and show the maximum. Declare a function called max_two that compares the numbers and returns the maximum

```c++
#include <iostream>
#include<cmath>
using namespace std;

int max_two(int x,int y){
    if (x>y)
    {
        return x;
    }
    else if (y>x)
    {
        return y;
    }
}

int main()
{
    int num1,num2 ;
    cout<<"enter the first number :"<<endl;
    cin >> num1;
    cout<<"enter the second number :"<<endl;
    cin >> num2;
    int m = max_two(num1,num2);
    cout<< m ;




    return 0;
}

```

4-Write a program that asks the user for an integer number and find the sum of all natural numbers up to that number

```c++
#include <iostream>
#include<cmath>
using namespace std;

int num(int x){
    int sum=0;
    for (int i = 0 ;i<=x ;i++)
    {
        sum+=i;
    }
    return sum ;
}

int main()
{
    int num1;
    cout<<"enter the first number :"<<endl;
    cin >> num1;
    int x=num(num1);
    cout << "the sum is :"<<x;




    return 0;
}

```

5-C++ program to print all Even and Odd numbers from 1 to N

```c++
#include <iostream>
#include<cmath>
using namespace std;

void even(int N)
{

    cout << "Even numbers from 1 to " << N << ": ";
    for (int i = 1; i <= N; i++) {
        if (i % 2 == 0) {
            cout << i << " ";
        }
    }
}
void odd(int N)
{
    cout << "\nOdd numbers from 1 to " << N << ": ";
    for (int i = 1; i <= N; i++) {
        if (i % 2 != 0) {
            cout << i << " ";
        }
    }
}

int main() {
    int N;
    cout << "Enter the value of N: ";
    cin >> N;
    even(N);
    odd(N);



    return 0;
}





```

6- Write a program to swap between two numbers by the function?

```c++
#include <iostream>
#include<cmath>
using namespace std;

void swap(int x,int y )
{
    int temp ;
    temp = y;
    y = x ;
    x = temp ;
    cout <<x<<" "<<y;
}

int main() {
    int a,b ;
    cout<<"enter two numbers :";
    cin >>a>>b ;
    cout <<"after swaping :";
    swap(a,b);



    return 0;
}





```

7- c++ function that finds average, sum, min and max of n numbers

```c++
#include <iostream>
#include<cmath>
using namespace std;

void res(int n)
{
    int max , min , sum =0 ;
    int response ;

    for (int i =1 ; i <=n ;i++)
    {
        cout<<"enter the number :";
        cin >> response ;
        if (i == 1)
        {
            max = response;
            min = response;
        }
        if (min > response)
        {
            min = response ;
        }
         if (max < response)
        {
            max = response ;
        }
        sum+=response ;
    }
    cout<<"sum is :"<<sum <<endl;
    cout<<"average is :"<<sum/n  <<endl ;
    cout<<"min is :"<<min <<endl;
    cout<<"max is :"<<max <<endl ;
}


int main() {
  int x ;
  cout<<"enter x";
  cin >>x;
  res(x);



    return 0;
}





```

