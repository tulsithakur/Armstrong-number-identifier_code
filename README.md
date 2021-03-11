# Armstrong-number-identifier_code
#include<iostream.h>
#include<conio.h>
void main()
{
long int orignum, num, rem, sum=0;
clrscr();
cout<< "enter a positive integer \n";
cin>>	orignum;
num=orignum;
while (num !=0)
{

rem= num% 10;
sum += rem*rem*rem;

num= num/10;
}
if(sum==orignum)
cout<< orignum <<" is an amstrong number \n";
else
cout<< orignum <<"is not an amstrong number \n";
cout<<"\nBY TULSI THAKUR";

getch();
}
