#include<stdio.h>
int main(){
    int i,j,num=1,n=3;
    char ch='A' ;
    printf("---PATTERN 1---\n");
    for(i=1;i<=3;i++){
        for(j=1;j<=i;j++){
            printf("*");
        }
        printf("\n");
    }
    for(i=2;i>=1;i--){
        for(j=1;j<=i;j++){
            printf("*");
        }
        printf("\n");
    }
    printf("---PATTERN 2---\n");
    for(i=1;i<=3;i++){
        for(j=1;j<=i;j++){
            printf("%d",j);
        }
        printf("\n");
    }
    for(i=2;i>=1;i--){
        for(j=1;j<=i;j++){
            printf("%d",j);
        }
        printf("\n");
    }
    printf("---PATTERN 3---\n");
    for(i=1;i<=3;i++){
        for(j=1;j<=i;j++){
            printf("%d",num++);
        }
        printf("\n");
    }
    for(i=2;i>=1;i--){
        for(j=1;j<=i;j++){
            printf("%d",num++);
        }
        printf("\n");
    }
    printf("---PATTERN 4---\n");
    for(i=1;i<=3;i++){
        ch='A';
        for(j=1;j<=i;j++){
            printf("%c",ch++);
        }
        printf("\n");
    }
    for(i=2;i>=1;i--){
        ch='A';
        for(j=1;j<=i;j++){
            printf("%c",ch++);
        }
        printf("\n");
    }
    printf("---PATTERN 5---\n");
    for(i=1;i<=3;i++){
        for(j=1;j<=i;j++){
            printf("%c",ch++);
        }
        printf("\n");
    }
    for(i=2;i>=1;i--){
        for(j=1;j<=i;j++){
            printf("%c",ch++);
        }
        printf("\n");
    }
    printf("---PATTERN 6---\n");
    for(i=n;i>=1;i--){
        for(j=1;j<=n - i;j++)
        printf(" ");
        for(j=1;j<=2*i-1;j++)
        printf("*");
        printf("\n");
    }
    for(i=2;i<=n;i++){
        for(j=1;j<=n - i;j++)
        printf(" ");
        for(j=1;j<=2*i-1;j++)
        printf("*");
        printf("\n");
    }
    printf("---PATTERN 7---\n");
    for(i=5;i>=1;i-=2){
        for(j=0;j<(5-i)/2;j++)
        printf(" ");
        for(j=1;j<=i;j++)
        printf("%d",num++);
        printf("\n");
    }
    for(i=3;i<=5;i+=2){
        for(j=0;j<(5-i)/2;j++)
        printf(" ");
        for(j=1;j<=i;j++)
        printf("%d",num++);
        printf("\n");
    }
    printf("---PATTERN 8---\n");
    for(i=5;i>=1;i-=2){
        for(j=0;j<(5-i)/2;j++)
        printf(" ");
        for(j=1;j<=i;j++)
        printf("%c",ch++);
        printf("\n");
    }
    for(i=3;i<=5;i+=2){
        for(j=0;j<(5-i)/2;j++)
        printf(" ");
        for(j=1;j<=i;j++)
        printf("%c",ch++);
        printf("\n");
    }
            
    
    return 0;
}
