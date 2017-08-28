/***exceptionaL****/
#include<iostream.h>
#include<conio.h>
void division(double x,double y)
{
cout<<"inside function";
try
{
if(y==0.0)
throw y;
else 
cout<<"division="<<x/y;
catch(double)
{
cout<<"caught double inside function ";
throw;
}
cout<<"end of function";
}
void main()
{
cout<<"inside main";
}
try
{
divide(10.5,2.0);
divide(20.8,4.6);
}
catch(double)
{
cout<<"caught double inside main";
}
cout<<"end of main";
}
