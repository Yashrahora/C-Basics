# C-Basics
C ++ basic codes will save here

#this is the code to print square patterns

#include<iostream>
using namespace std;

int main() {
    int n = 4;
    
    int num = 1;
    
    for(int i=0; i<n; i++){
        for(int j=0; j<n; j++){
            cout<< num << " ";
           num++;
        }
        cout<< endl;
    }
    return 0;
}