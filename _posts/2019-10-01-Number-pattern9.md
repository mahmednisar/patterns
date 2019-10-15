---
title: Number Pattern 9
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 9
---


## Pattern 9

```
    1 
   1 2 
  1 2 3 
 1 2 3 4 
1 2 3 4 5 
 1 2 3 4 
  1 2 3 
   1 2 
    1 

```

```

#include <stdio.h>
#include <stdlib.h>
 
int main(void) {
    int i, j, k;
 
            for (i = 1; i <= 5; i++) {
                for (j = 1; j <= 5 - i; j++)
                    printf(" ");
 
                for (k = 1; k <= i; k++)
                    printf("%d ", k);
 
                printf("\n");
            }
 
            for (i = 1; i <= 4; i++) {
                for (j = 1; j <= i; j++)
                    printf(" ");
 
                for (k = 1; k <= 5 - i; k++)
                    printf("%d ", k);
 
                printf("\n");
            }
}
 ```