---
title: Number Pattern 12
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 12
---


## Pattern 12

```
1 2 3 4 5 
 2 3 4 5 
  3 4 5 
   4 5 
    5 
   4 5 
  3 4 5 
 2 3 4 5 
1 2 3 4 5 

```

```


#include <stdio.h>
int main ()
{
    int n = 5;
     
     
    for (int i = 1; i <= n; i++) 
    {
        for (int j = 1; j < i; j++) 
        {
            printf(" ");
        }
         
        for (int k = i; k <= n; k++) 
        { 
            printf("%d", k); 
            printf(" ");
        } 
         
        printf("\n"); 
    } 
     
    for (int i = n-1; i >= 1; i--) 
    {
         for (int j = 1; j < i; j++) 
        {
            printf(" ");
        }
        for (int k = i; k <= n; k++)
        {
            printf("%d", k); 
            printf(" ");
        }
         
        printf("\n");
    }
    
  return 0;
}
```