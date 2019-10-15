---
title: Mixed Pattern 1
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 1

---


## Pattern 8

```
1****
12***
123**
1234*
12345

```

```
 
#include <stdio.h>
#include <stdlib.h>
 
int main(void) {
    int i, j, k;
    int n = 5;
    for (i = 1; i <= n; i++) {
        for (j = 1; j <= i; ++j)
            printf("%d", j);
 
        for (k = n - i; k >= 1; k--)
            printf("*");
 
        printf("\n");
    }
}
 ```