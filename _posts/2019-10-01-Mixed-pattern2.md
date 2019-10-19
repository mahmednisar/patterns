---
title: Mixed Pattern 2
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 2

---


## Pattern 2

```
 1 
 1 *
 1 * 3 
 1 * 3 *
 1 * 3 * 5 
 1 * 3 * 5 *

```

```
 #include<stdio.h>
void main()
{
    int i,j;
    for(i=1; i<=6; i++){
        for(j=1; j<=i; j++){
            if(j%2==0){
                printf("*");
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