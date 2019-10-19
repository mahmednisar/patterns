---
title: Mixed Pattern 5
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 5

---


## Pattern 5

```
 *  *  *  *  *  6 
 *  *  *  *  5  6 
 *  *  *  4  5  6 
 *  *  3  4  5  6 
 *  2  3  4  5  6 
 1  2  3  4  5  6 

```

```
#include<stdio.h>
void main()
{
    int i,j,prev1=0,prev2=0, prev3=0;
    for(i=1; i<=6; i++){
        for(j=1; j<=6; j++){
            if(i<=6-j){
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