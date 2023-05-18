IF
(it only read the commend given in if eg[ if(a<b)])

#include <stdio.h>
void main() {
    int a,b;
    printf("\nif statement");
    printf("\nEnter the A value:");
    scanf("%d",&a);
    printf("\nEnter the B value:");
    scanf("%d",&b);
    if(a<b)
    {
     printf("\nVariable %d is less than %d",a,b);   
    }
    
    if(a>b)
    {
     printf("\nVariable %d is greater than %d",a,b);   
    }
    
    if(a==b)
    {
     printf("\nVariable %d is equal than %d",a,b);   
    }
}


IF ELSE
(it read if condition and if its true printf (in if) or it is false it print what is in else)
#include <stdio.h>
void main() {
    int a,b;
    printf("\nif else statement");
    printf("\nEnter the A value:");
    scanf("%d",&a);
    printf("\nEnter the B value:");
    scanf("%d",&b);
    if(a<b)
    {
        printf("\n B=%d is Biggest value",b);   
    }
    else
    {
        printf("\n A=%d is Biggest value",a);   
    }
}

ELSE IF
(it is used to add another if else condition for the coad)
#include <stdio.h>
void main() {
    int a;
    printf("\nElse if statement");
    printf("\nEnter the A value:");
    scanf("%d",&a);
    if(a>1 && a<=17)
    {
        printf("\n B=%d You Can Not Apply ");   
    }
    else if(a>=18 && a<=35)
    {
        printf("\n A=%d You Can Apply");   
    }
    else
    {
        printf("Over Age");   
    }
}

NESTED IF
(add multiple number of if condition in same set braket  )
#include <stdio.h>
void main() {
    int a;
    printf("\nNested if statement");
    printf("\nEnter the A value:");
    scanf("%d",&a);
    if(a>50)
    {
        if(a<=100) 
        {
            printf("\nPass");
        }
        else
        {
            printf("\nInvalid Mark");
        }
    }
    else
    {
        printf("\nFail");
    }
}
