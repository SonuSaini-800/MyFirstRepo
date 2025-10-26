# MyFirstRepo
Hello i am new user
//find largest number in cpp


#include<iostream>
#include<climits>
using namespace std;
int main()
{ 
int arr[] = {3,8,1,9,5};
int size = sizeof(arr)/sizeof(int);
int largest = INT_MIN;
int index = -1;
for(int i =0;i<size;i++){
   if(arr[i]>largest){
    largest = arr[i];
    index = i;
   }
    
}
cout<<index<<endl;
cout<<largest;

return 0;
    }

