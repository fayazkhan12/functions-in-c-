# functions-in-c-
Questions on fuctions in c++


// functions

// q1 Combinations and permutation....

#include<iostream>
using namespace std;


int main()

{
    int n;
 cout<<"enter the n..";
 cin>>n;
 
 int r;
 cout<<"enter the r ";
 cin>>r;
int nfact=1;
for(int i=2;i<=n;i++)
{
    nfact *= i;
   
}
int rfact=1;
for(int i=2;i<=r;i++)
{
    rfact *= i;
   
}
int nrfact=1;
for(int i=2;i<=n-r;i++)
{
   nrfact *= i;
   
}

int ncr=nfact/(rfact*nrfact);

cout<<ncr;

 
 
    
}
