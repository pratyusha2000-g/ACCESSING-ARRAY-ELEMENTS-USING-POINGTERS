# ACCESSING-ARRAY-ELEMENTS-USING-POINGTERS
#include <iostream>

using namespace std;
int main()
{
    int n,i;

    cout<< "Enter the number of elements: "<<endl;
    cin>>n;
    int a[n];
    cout<<"Enter "<<n<<"numbers";
    for (int i = 0; i < n; ++i)
        cin>>a[i];


    cout<<"The numbers entered: \n";
    for (int i = 0; i < n; ++i)
        cout<< *(a + i)<<" ";
    return 0;
}    
