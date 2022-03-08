//easiest method to perform sorting operation in cpp by jainil soni
#include<iostream>
using namespace std;
int main()
{
	
	int i,j,swap,udf;
	cout<<"Enter the size of an array:";
	cin>>udf;
	
	int arr[udf];
	
	for(i=0; i<udf; i++)
	{
		cin>>arr[i];
	}
	
	for(i=0; i<udf; i++)
	{
		cout<<arr[i]<<" ";
	}
	
	cout<<"\n Before Sorting \n";
	
	for(j=0; j<udf*udf; j++){
	for(i=0; i<udf; i++)
	{
		if(arr[i] > arr[i+1])
		{
			swap = arr[i];
			arr[i] = arr[i+1];
			arr[i+1] = swap;	
		}
	}
						}
	
	cout<<"\n -----After Sorting----- \n";
	
	for(i=0; i<udf; i++)
	{
		cout<<arr[i]<<" ";
	}

	return 0;
}
