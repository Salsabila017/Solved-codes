# Solved-codes
CF_Problem(A. Football)

Solve:
#include<bits/stdc++.h>
using namespace std;
 
int main()
{
    string a;
    int s=0,p=0;
    cin>>a;
    for(int i=0; i<a.size();i++)
   {
       if(a[i]==a[i+1])
       {
            s++;
            if(s==6)
            {
                p=1;
                break;
            }
       }
       else
       {
           s=0;
       }
   }
   if(p==1)
   {
       cout<<"YES"<<endl;
   }
   else
   {
       cout<<"NO"<<endl;
   } 
}

