---
title: Mixed Pattern 3
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 3

---


## Pattern 2

```
 1 
 *  * 
 1  2  3 
 *  *  *  * 
 1  2  3  4  5 
 *  *  *  *  *  * 


```

```
#include<stdio.h>
void main()
{
    int i,j;
    for(i=1; i<=6; i++){
        for(j=1; j<=i; j++){
            if(i%2==0){
                printf(" * ");
            }
            else
            {
                printf(" %d " ,j );
            }
            
        }
        printf("\n");
    }
}
```