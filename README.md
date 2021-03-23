# online_test




#include <stdio.h>
int main() 
{ 
	int arr[5][2]; 
	arr[0][0] = 11; arr[0][1] = 20; 
	arr[1][0] = 30; arr[1][1] = 40; 
	arr[2][0] = 5;  arr[2][1] = 10; 
	arr[3][0] = 40; arr[3][1] = 30; 
	arr[4][0] = 10; arr[4][1] = 5; 
	
	printf("%d\t",arr[1][0]);
	printf("%d\n",arr[1][1]);
	printf("%d\t",arr[2][0]);
	printf("%d\n",arr[2][1]);	
} 
