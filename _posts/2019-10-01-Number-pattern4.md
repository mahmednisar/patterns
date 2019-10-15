---
title: Number Pattern 4
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 4
---


## Pattern 1

```
12345
1234
123
12
1

1
12
123
1234
12345
```

```

#include <stdio.h>
#include <stdlib.h>
 
int main(void) {
    int n = 5;
    int i, j;
    for (i = n; i >= 0; i--) {
        for (j = 1; j <= i; j++)
            printf("%d", j);
        printf("\n");
    }
 
    for (i = 1; i <= n; i++) {
        for (j = 1; j <= i; j++)
            printf("%d", j);
        printf("\n");
    }
    printf("\n");
}
 
 ```