#include<iostream>
using namespace std;

void print_leader(int a[], int n)
{
	int leader = INT_MIN;
	for(int i = n-1; i >= 0; i--)
	{
		if(leader < a[i])
		{
			leader = a[i];
			cout<<leader<<" ";
		}
	}
}
int main()
{
	int n;
	cin>>n;
	int arr[n];
	for(int i = 0; i < n; i++)
	{
		cin>>arr[i];
	}
	print_leader(arr,n);
	return 0;
}
