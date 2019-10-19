---
title: Mixed Pattern 4
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 4

---


## Pattern 4

```
 * 
 *  * 
 *  2  * 
 *  2  3  * 
 *  2  3  4  * 
 *  2  3  4  5  * 
 *  2  3  4  5  6  * 
 *  *  *  *  *  *  *  * 


```

```
#include<stdio.h>
void main()
{
    int i,j;
    for(i=1; i<=8; i++){
        for(j=1; j<=i; j++){
            if(i==8||j==1||i==j){
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