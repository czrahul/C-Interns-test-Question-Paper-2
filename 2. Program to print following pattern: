#include<iostream>
using namespace std;

int main()
{
	int n;
	cin>>n;
	for(int i = 0; i < 2*n; i++)
	{
		if(i <= n)
		{
			for(int j = 0; j < 2*n; j++)
			{
				if(j <= i || j >= 2*n-i-1)
				{
					cout<<'*'<<" ";
				}
				else
				{
					cout<<"  ";
				}
			}
		}
		else
		{
			int t = n- i%n;
			for(int j = 0; j < 2*n; j++)
			{
				if(j < t || j > 2*n-t-1)
				{
					cout<<'*'<<" ";
				}
				else
				{
					cout<<"  ";
				}
			}
		}
		
		cout<<"\n";
	}
	return 0;
}
