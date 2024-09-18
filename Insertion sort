#include <bits/stdc++.h>
using namespace std;

int main() {
    int n;
    cin>>n;
    int arr[n];
    for(int i=0;i<n;i++){
        cin>>arr[i];
    }
    for(int i=1;i<n;i++){
        int element=arr[i];
        int j=i-1;
        while(j>=0 && arr[j]>element){
            arr[j+1]=arr[j];
            j--;
        }
        arr[j+1]=element;
        for(int k=0;k<n;k++){
            cout<<arr[k]<<" ";
        }cout<<endl;
    }
    
    for(int i=0;i<n;i++){
        cout<<arr[i]<<" ";
    }
    
}
