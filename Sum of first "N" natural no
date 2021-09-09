#include <bits/stdc++.h>
using namespace std;

//using Recursion Which has time compaxity of order(n) and space complaxit(n)
int SUM_Recursion(int n)
{
    if(n==0)
    {
        return 0;
    }
    else
    return SUM_Recursion(n-1)+n;
}

//Using Formula Which hai time "constant" complaxity 
int SUM_formula(int n)
{
    return (n*(n+1))/2;
}

//using Loop Which has time compaxity of order(n) and space complaxit()
int SUM_loop(int n)
{
    int sum=0;
    for(int i=1;i<=n;i++)
    {
      sum=sum+i;
    }
    return sum;
}

int main()
{
    int a;
    cin>>a;
    cout<<"Sum using Recursion function "<<SUM_Recursion(a)<<endl;
    cout<<"Sum using Formula "<<SUM_formula(a)<<endl;
    cout<<"Sum using Loop "<<SUM_loop(a)<<endl;

    return 0;
}
