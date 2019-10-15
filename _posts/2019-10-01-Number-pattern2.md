---
title: Number Pattern 2
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 2
---


## Pattern 2

```
1
22
333
4444
55555
```

```
 
#include <stdio.h>
#include <stdlib.h>
 
int main(void) {
    int count = 5;
    int i, j;
    for (i = 1; i <= count; i++) {
        for (j = 1; j <= i; j++) {
            printf("%d", i);
        }
        printf("\n");
    }
 
}
 
```