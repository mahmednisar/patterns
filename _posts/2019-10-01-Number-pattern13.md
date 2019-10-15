---
title: Number Pattern 13
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 13
---


## Pattern 13

```
1
01
101
0101
10101

```

```
#include <stdio.h>
 
int main ()
{
     int n, p, q;
     
        n = 5;
        for (int i = 1; i <= n; i++)
        {
            if (i % 2 == 0)
            { p = 1; q = 0; }
            else
            { p = 0; q = 1; }
            for (int j = 1; j <= i; j++)
                if (j % 2 == 0)
                    printf("%d", p);
                else
                    printf("%d", q);
            printf("\n");
        }
  return 0;
}
```