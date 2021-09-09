#include <bits/stdc++.h>
using namespace std;

//using Recursion Which has time compaxity of order(n) and space complaxit(n)
int Fact_Recursion(int n)
{
    if(n==0)
    {
        return 1;
    }
    else
    return Fact_Recursion(n-1)*n;
}

//using Loop Which has time compaxity of order(n) and space complaxit()
int Fact_loop(int n)
{
    int Product=1;
    for(int i=1;i<=n;i++)
    {
      Product=Product*i;
    }
    return Product;
}

int main()
{
    int a;
    cin>>a;
    cout<<"Factorial using Recursion function "<<Fact_Recursion(a)<<endl;
    cout<<"Factorial using Loop "<<Fact_loop(a)<<endl;

    return 0;
}
