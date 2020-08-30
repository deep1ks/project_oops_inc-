# project_oops_inc++
#include<iostream>

using namespace std;
class time  //a class has defined
{
	public:
int hours,minutes,seconds,total_seconds;	
};
int main()
{
	time t1;
	cout<<"Enter time:"<<endl;
	cout<<"Hours? ";
	cin>>t1.hours;
	cout<<"Minutes? ";
	cin>>t1.minutes;
	cout<<"Seconds? ";
	cin>>t1.seconds;
	t1.total_seconds=t1.hours*3600+t1.minutes*60+t1.seconds;
	cout<<"The time is ="<<"0"<<t1.hours<<":0"<<"t1.seconds"<<":0"<<t1.seconds<<endl;//it shows hours minutes and seconds
	cout<<"Time in total seconds:"<<t1.total_seconds; // total time in seconds	
return 0;	
}
