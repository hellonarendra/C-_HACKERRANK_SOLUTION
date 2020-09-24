-------------------EMPLOYEE SALARY------------------------------------------------

#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;

class employee{
    int r;
    float s1,s2,s3;
    char name[31];
    public:
           employee()
           {
               r = 0;
               s2 = 0;
               s1 = 0;
               s3 = 0;
           }
         void input()
         {
             cin>>r>>name>>s1>>s2>>s3;
             cout<<name<<"\n"<<r<<"\n"<<s1<<"\n"<<s2<<"\n"<<s3<<"\n"<<(s1 + s2 - s3)<<"\n";
         }
         void Display()
         {
             cout<<name<<"\n"<<r<<"\n"<<s1*1.25<<"\n"<<s2*1.25<<"\n"<<s3*1.25<<"\n"<<(s1 + s2 - s3)*1.25<<"\n";
         }
};

int main() {
    employee o;
    int n;
    int i = 2;
    while(i--)
    {
        cin>>n;
        if(n==1)
        o.input();
        else
        o.Display();
    }
        return 0;
}

----------------------------------------STUDENT ------------------------------------------------------------------

