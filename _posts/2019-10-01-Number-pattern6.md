---
title: Number Pattern 6
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 6
---


## Pattern 6

```
    1 
   1 2 
  1 2 3 
 1 2 3 4 
1 2 3 4 5 

```

```

#include <stdio.h>
#include <stdlib.h>
 
int main(void) {
    int n = 5, i, j, k;
 
    for (i = 1; i <= n; i++) {
        for (j = 1; j <= n - i; j++) {
            printf(" ");
        }
        for (k = 1; k <= i; k++) {
            printf("%d ", k);
        }
        printf("\n");
    }
}
 ```