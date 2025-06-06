# convert-given-year-into-roman-equivalent.c
// C program to convert any given year into its roman equivalent. 
// C program to convert any given year into its roman equivalent.
#include <stdio.h>

int main() {
int n;
printf("enter no=");
    scanf("%d",&n);
    
    while(n){
        if(n>=1000){
         printf("m");
         n=n-1000;
        }
        else if(n>=500){
         printf("d");
         n=n-500;
        }
        else if(n>=100){
         printf("c");
         n=n-100;
        }
        else if(n>=50){
         printf("l");
         n=n-50;
        }
        else if(n>=10){
         printf("x");
         n=n-10;
        }
        else if(n>=5){
         printf("v");
         n=n-5;
        }
        else if(n>=1){
         printf("i");
         n=n-1;
        }
    }

    return 0;
}
