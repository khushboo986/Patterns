#include<stdio.h>
int main(){
    int i,j,num=1,n=5;
    char ch='A' ;
    char ch1='A';
    char ch2='A';
    char ch3='a';
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
            printf("%c",ch1++);
        }
        printf("\n");
    }
    for(i=2;i>=1;i--){
        for(j=1;j<=i;j++){
            printf("%c",ch1++);
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
        printf("  ");
        for(j=1;j<=i;j++)
        printf("%d",num++);
        printf(" \n");
    }
    for(i=3;i<=5;i+=2){
        for(j=0;j<(5-i)/2;j++)
        printf("  ");
        for(j=1;j<=i;j++)
        printf("%d",num++);
        printf(" \n");
    }
    printf("---PATTERN 8---\n");
    for(i=5;i>=1;i-=2){
        for(j=0;j<(5-i)/2;j++)
        printf(" ");
        for(j=1;j<=i;j++)
        printf("%c",ch2++);
        printf("\n");
    }
    for(i=3;i<=5;i+=2){
        for(j=0;j<(5-i)/2;j++)
        printf(" ");
        for(j=1;j<=i;j++)
        printf("%c",ch2++);
        printf("\n");
    }
     
    printf("---PATTERN 9---\n");
    for(i = 1; i <= 5; i++) {
        for(j = 1; j <= 5; j++) {
            
                printf("*");
            }
        }
        printf("\n");

    printf("---PATTERN 10---\n");
    for(i = 1; i <= 5; i++) {
        for(j = 1; j <= 5; j++) {
            if(j == 1 || j == 5 || i == 3) {
                printf("%c ", ch++);
            } else {
                printf("  ");
            }
        }
        printf("\n");
    }
    printf("---PATTERN 11---\n");
    for(i = 1; i <= n; i++) {
        for(j = 1; j <= n; j++) {
            if(i == 1 || i == n || j == 1 || j == n)
                printf("* ");
            else
                printf("  ");
        }
        printf("\n");
    }
    printf("---PATTERN 12---\n");
    for(i = 1; i <= 4; i++) {
        for(j = 1; j <= 4; j++) {
            if(i == 1 || i == 4 || j == 1 || j == 4)
                printf("%2d ", num++);
            else
                printf("   ");
        }
        printf("\n");
    }
    printf("---PATTERN 13---\n");
    for(i = 1; i <= 4; i++) {
        for(j = 1; j <= 4; j++) {
            if(i == 1 || i == 4 || j == 1 || j == 4)
                printf("%c ", ch++);
            else
                printf("  ");
        }
        printf("\n");
    }
    printf("---PATTERN 14---\n");
    for(i = 1; i <= n; i++) {
        for(j = 1; j <= i; j++) {
            if(j == 1 || j == i || i == n)
                printf("* ");
            else
                printf("  ");
        }
        printf("\n");
    }
    printf("---PATTERN 15---\n");
    for(i = 1; i <= 5; i++) {
        for(j = 1; j <= i; j++) {
            if(j == 1 || j == i || i == 5)
                printf("%c ", ch3++);
            else
                printf("  ");
        }
        printf("\n");
    }
    printf("---PATTERN 16---\n");
    for(i = 1; i <= n; i++) {
        for(j = i; j < n; j++)
            printf(" ");

        for(j = 1; j <= i; j++) {
            if(j == 1 || j == i || i == n)
                printf("* ");
            else
                printf("  ");
        }
        printf("\n");
    }
    printf("---PATTERN 17---\n");
    for(i = 1; i <= n; i++) {
        for(j = i; j < n; j++)
            printf("  ");

        for(j = 1; j <= i; j++)
            printf("%d   ", num++);

        printf("\n");
    }
    printf("---PATTERN 18---\n");
    for(i = 5; i >= 1; i -= 2) {
        for(j = 0; j < (5 - i) / 2; j++)
            printf("  ");

        for(j = 1; j <= i; j++)
            printf("%d ", num++);

        printf("\n");
    }

    return 0;
}
