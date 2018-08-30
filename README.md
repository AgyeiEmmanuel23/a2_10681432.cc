# a2_10681432.cc
#include <iostream>
#include <math.h>
using namespace std;
int main ()
{
	
int num, i, fact, inum; 
cout<< "Please enter any number\n";
cin>>num;
inum = sqrt(num);
for (i=2; i<num; i++)

	if (num% i == 0)
	{
		fact = 0;
		break;
	}
	else 
	fact = 1;
	if (fact)
	cout<<num << "is prime\n"<< endl;
	else
	cout<<num << "is NOT prime\n" << endl;
	
	

return 0;

}
