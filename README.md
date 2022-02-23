# Enter-an-integer-from-the-keyboard.-Check-if-a-number-is-a-perfect-square-
Enter an integer from the keyboard. Check if a number is a perfect square?
#include<stdio.h>
#include<conio.h>
#include<math.h>
main()
{    
    int x,y;
    printf("Nhap x=");
    scanf("%d",&x);  
    y=sqrt(x);
    if(x==y*y)
    {
        printf("%d la so chinh phuong",x);
    } 
    else
    {
        printf("%d khong phai la so chinh phuong",x);        
    }
    getch();    
}    
