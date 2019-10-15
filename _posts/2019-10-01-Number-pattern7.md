---
title: Number Pattern 7
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 7
---


## Pattern 7

```
5
54
543
5432
54321

```

```
#include <stdio.h>
#include <stdlib.h>
 
int main(void) {
    int i = 5;
    while (i >= 1) {
        int j = 5;
        while (j >= i) {
            printf("%d", j);
            j--;
        }
        i--;
        printf("\n");
    }
}
 ```