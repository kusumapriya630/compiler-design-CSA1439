#include <stdio.h>
#include <string.h>

int main() 
{
    char n1[100], n2[100], n3[100];
    printf("Enter expression 1: ");
    scanf("%s", n1);
    printf("Enter expression 2: ");
    scanf("%s", n2);
    printf("Enter expression 3: ");
    scanf("%s", n3);
    //printf("Expression 1 is %s\n", n1);
    //printf("Expression 2 is %s\n", n2);
    //printf("Expression 3 is %s\n", n3);
    if (strcmp(n1, n2) == 0)
    {
        printf(" After Eliminating Common Subexpression \n %s\n %s \n", n1, n3);
    }
    else if (strcmp(n1, n3) == 0)
    {
        printf("After Eliminating Common Subexpression  \n %s\n %s\n", n1, n2);
    }
    else if (strcmp(n2, n3) == 0)
    {
        printf("After Eliminating Common Subexpression \n %s\n %s\n", n1, n2);
    }
    else 
    {
        printf("No common subexpression\n");
    }
}
