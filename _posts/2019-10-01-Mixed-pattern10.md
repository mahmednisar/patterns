---
title: Mixed Pattern 10
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 10

---


## Pattern 10

```
 *  *  *  *  *  1  *  *  *  *  * 
 *  *  *  *  1  2  1  *  *  *  * 
 *  *  *  1  2  3  2  1  *  *  * 
 *  *  1  2  3  4  3  2  1  *  * 
 *  1  2  3  4  5  4  3  2  1  * 
 1  2  3  4  5  6  5  4  3  2  1 
 *  1  2  3  4  5  4  3  2  1  * 
 *  *  1  2  3  4  3  2  1  *  * 
 *  *  *  1  2  3  2  1  *  *  * 
 *  *  *  *  1  2  1  *  *  *  * 
 *  *  *  *  *  1  *  *  *  *  * 


```

```
#include<stdio.h>
void main()
{
    int i,j,k;
    for(i=1; i<=6; i++){
        for(k=1; k<=6-i; k++){
            printf(" * ");
        }
           for(j=1; j<i; j++){
            printf(" %d ",j);
        }
        for(j=i; j>=1; j--){
            printf(" %d ",j);
        }
        for(k=i; k<=5; k++){
            printf(" * ");
        }
        printf("\n");
        
    }
    for(i=1; i<6; i++){
        for(k=1; k<=i; k++){
            printf(" * ");
        }

        for(j=1; j<=6-i; j++){
            printf(" %d ", j);
        }

          for(j=6-i-1; j>=1; j--){
            printf(" %d ",j);
        }
        
          for(j=1; j<=i; j++){
            printf(" * ");
        }
        
        printf("\n");
        
    }
}
```