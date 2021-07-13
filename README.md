# Game-A-Thon
## Name : Piyusha Barapatre
Problem Statement 1 : Swap Numbers Using Temporary Variable
Input : A = 1 , B = 2 , Output : A = 2 , B = 1

'''c
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
'''


