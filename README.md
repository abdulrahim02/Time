# Time
Created by Abdulrahim Mulla.


//Time
#include <iostream>
using namespace std;

int main()
{
	int hh=0, mm=0, ss=0, ts=0 ;
	
	cout<<"Hours?  ";
	cin>>hh;
	cout<<"Minutes?  ";
	cin>>mm;
	cout<<"Seconds?  ";
	cin>>ss;

	
	if(hh>=0 && hh<=24 || mm>0 && mm<=60 || ss>0 && ss<=60)
	{
		cout<<"Time in HH:MM:SS\n";
		cout<<"The Time is  =  "<<hh<<": "<<mm<<": "<<ss;
		ts=hh*mm*ss;
		cout<<"\nTime in Total Seconds = "<<ts;	
	}
	
	else
	{
	cout<<"\nTime in total seconds is INVALID ";	
	}
	return 0;
}

