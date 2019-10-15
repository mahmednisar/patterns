---
title: Number Pattern 1
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 1
---


## Pattern 1

```
        1
       121
      12321
     1234321
    123454321
   12345654321
  1234567654321
 123456787654321
12345678987654321
```

```


#include <stdio.h>
#include <stdlib.h>
 
int main(void) {
    int num, space, i, j, k;
 
    printf("Enter a number between 1 to 9 : \n");
 
    scanf("%d", &num);
 
    space = num - 1;
 
    for (i = 1; i <= num; i++) {
        for (space = 1; space <= (num - i); space++) {
            printf(" ");
        }
 
        for (j = 1; j <= i; j++) {
            printf("%d", j);
        }
 
        for (k = (i - 1); k >= 1; k--) {
            printf("%d",k);
        }
 
        printf("\n");
 
    }
 
}
 


 ```