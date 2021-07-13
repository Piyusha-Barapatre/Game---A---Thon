# Game-A-Thon
## Name : Piyusha Barapatre
### Problem Statement 1 : Swap Numbers Using Temporary Variable
Test Case : Input : A = 1 , B = 2 , Output : A = 2 , B = 1

```c
#include<stdio.h>
int main() {
      int first, second, temp;
      printf("Enter first number, A =  ");
      scanf("%d", &first);
      printf("Enter second number, B = ");
      scanf("%d", &second);
      temp = first;
      first = second;
      second = temp;
      printf("\nAfter swapping, A = %d\n", first);
      printf("After swapping, B = %d", second);
      return 0;
}
```

###  Problem Statement 2 : Program to Multiply Two Numbers
Test Case : Input : A = 10 , B = 20 , Output : C = 200

```c 
#include <stdio.h>
int main() {
    int A, B, C;
    printf("Enter two numbers: ");
    scanf("%d %d", &A, &B);  
    product = A * B;
    printf("C = %d", product);
    return 0;
}
```




