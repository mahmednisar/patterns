---
title: Number Pattern 8
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 8
---


## Pattern 8

```
   1
  212
 32123
4321234
 32123
  212
   1

```

```

#include <stdio.h>
 
int main()
{
    for (int i = 1; i <= 4; i++)
        {
            int n = 4;
 
            for (int j = 1; j <= n - i; j++)
            {
                printf(" ");
            }
            for (int k = i; k >= 1; k--)
            {
                printf("%d", k);
            }
            for (int l = 2; l <= i; l++)
            {
                printf("%d", l);
            }
 
            printf("\n");
        }
 
        for (int i = 3; i >= 1; i--)
        {
            int n = 3;
 
            for (int j = 0; j <= n - i; j++)
            {
                printf(" ");
            }
            for (int k = i; k >= 1; k--)
            {
                printf("%d", k);
            }
            for (int l = 2; l <= i; l++)
            {
                printf("%d", l);
            }
 
            printf("\n");
        }
     
    return 0;
}
 ```