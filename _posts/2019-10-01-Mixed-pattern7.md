---
title: Mixed Pattern 7
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 7

---


## Pattern 7

```
 6  5  4  3  2  1 
 *  5  4  3  2  1 
 *  *  4  3  2  1 
 *  *  *  3  2  1 
 *  *  *  *  2  1 
 *  *  *  *  *  1 


```

```
#include<stdio.h>
void main()
{
    int i,j;
    for(i=6; i>=1; i--){
        for(j=6; j>=1; j--){
            if(i<j){
                printf(" * ");
            }
            else
            {
                printf(" %d ", j);
            }
        



        }
        printf("\n");
    }
}
```