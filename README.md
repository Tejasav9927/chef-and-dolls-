# chef-and-dolls-
#include <bits/stdc++.h>
#include <math.h>
using namespace std;

int main() {
	// your code goes here
	int t;
	cin>>t;
	while(t--)
	{
		int x;

		cin>>x;
		int a[x];
		for(int i=0;i<x;i++)
		{
			cin>>a[i];
		}
		for(int i=0;i<x;i++)
		{
			int c=0;
			for(int j=0;j<x;j++)
			{
            if(a[i]==a[j])
            {
            	c++;
            	
            }
			}
		
		 if(c%2!=0)
		 {
			cout<<a[i]<<endl;
			break;
		 }
	    }
    }
    return 0;
}
