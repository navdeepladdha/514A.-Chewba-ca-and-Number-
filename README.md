# 514A.-Chewba-ca-and-Number-



#include<bits/stdc++.h>
using namespace std;

int main(){
    string x;
    cin>>x;
    
    for(int i=0;i<x.size();i++){
      
      int digit=x[i]-'0'; //convert char to int
      int inverted=9-digit;
      
      if(inverted < digit && !(i==0 && digit==9)){
        x[i]=inverted+'0'; //convert int to char
      }
      
    }
    
    
    cout<<x<<endl;
    
    return 0;
    
}
