---
title: Mixed Pattern 6
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 6

---


## Pattern 6

```
 6  *  *  *  *  * 
 6  5  *  *  *  * 
 6  5  4  *  *  * 
 6  5  4  3  *  * 
 6  5  4  3  2  * 
 6  5  4  3  2  1 
```

```
#include<stdio.h>
void main()
{
    int i,j;
    for(i=1; i<=6; i++){
        for(j=6; j>=1; j--){
            if(j<=6-i){
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