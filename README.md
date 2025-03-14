# c-35
Tail recursion 
#include<stdio.h>
void tail(int n){
    if(n==0){
        printf("end of tail recursion");
        return;
    }

            printf("%d",n);
            tail(n-1);
    }
    int main(){
        tail(10);
        return 0;
    }
