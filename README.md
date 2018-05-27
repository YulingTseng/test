#include <iostream>
#include <iomanip>
using namespace std;
int main()
{
	double miles,kilometers;
	
	cin >>miles;
	
	kilometers=miles*1.6;
	cout <<fixed<<setprecision(1);
	cout <<kilometers<<endl;
	return 0;
}
