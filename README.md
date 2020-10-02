# CSE-Assignment-01

#include<stdio.h>
int main()
{
    int i,j;
    for (i=5;i>=1;i--)
    {
       for(j=1;j=<i;j++)
        {
            printf("*");
        }
    printf("\n");}
}


# CSE-Assignment-02


#include<stdio.h>
main(){
    
    int row,col,count=1;
    for(row=1;row<=5;row++){
        
        for(col=1;col<=row;col++)
        printf("%d ", count++);
        printf("\n");
    } 
}
