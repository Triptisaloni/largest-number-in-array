# largest-number-in-array in c and c++

C
#include<stdio.h> 
void main()
{
int a[7],i,large;
printf("Enter the numbers");
for(i=0;i<7;i++)
scanf("%d",&a[i]);

large = a[0];

for(i=1;i<7;i++)
{ if (a[i]> large)
large = a[i];
}
printf("largest number is %d", large);

getch();
}

C++
#include<iostream>
using namespace std;
int main(void)
{
int a[7],i,large;
cout<<"Enter the numbers"<<endl;
for(i=0;i<7;i++)
cin>>a[i];

large = a[0];

for(i=1;i<7;i++)
{ if (a[i]> large)
large = a[i];
}
cout<<"largest number is "<<large<<endl;


}
