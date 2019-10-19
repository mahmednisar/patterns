---
title: Mixed Pattern 8
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 8

---


## Pattern 8

```
 *  *  *  *  *  1 
 *  *  *  *  2  2  2 
 *  *  *  3  3  3  3  3 
 *  *  4  4  4  4  4  4  4 
 *  5  5  5  5  5  5  5  5  5 
 6  6  6  6  6  6  6  6  6  6 6 



```

```
#include<stdio.h>
void main()
{
    int i,j,prev1=0,prev2=0, prev3=0;
    for(i=1; i<=6; i++){
        for(j=1; j<=i+5; j++){
            if(i<=6-j){
                printf(" * ");
            }
            else
            {
                printf(" %d ", i);
            }
            



        }
        printf("\n");
        
    }
}
```