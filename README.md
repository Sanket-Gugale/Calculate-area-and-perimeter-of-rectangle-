# Calculate-area-and-perimeter-of-rectangle-
#include<stdio.h>
int main()
{
    int l,b,a,p;
    printf("Enter lenght of the  rectangle=\t");
    scanf("d",& l);
    printf("Enter breadth of the rectangle=\t");
    scanf("d"'& b);
    a=l*b;
    printf("\nArea of rectangle =%d",a);
    p=2*(l+b);
    printf("\nPerimeter of rectangle =%d",p);
    return 0;
}    
