# NEW-LEARENED-TOPICS
bitwise xor
#include <bits/stdc++.h>
using namespace std;

int main() {
  /*  //with the help xor we can swap the number;
    int a=4;
    int b=5;
    a=a^b;
    b=a^b;//a=a^b then b=a^b^b b==a{wkt value^samevalue is always 0}
    a=a^b;//a=a^b then a=a^b^a a==b;
    cout<<a<<" "<<b;*/
    int n;
    cin>>n;
    int s=0;
    int arr[n];
    for(int i=0;i<n;i++)
    {
        cin>>arr[i];
        s=s^arr[i];
        
    }
    cout<<s;
    
	
	return 0;
}
*********************************************************************************************************************************************************************
