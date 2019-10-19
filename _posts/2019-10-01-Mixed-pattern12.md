---
title: Mixed Pattern 12
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 12

---


## Pattern 12

```
 1  *  *  *  *  *  *  *  *  *  *  1 
 1  2  *  *  *  *  *  *  *  *  2  1 
 1  2  3  *  *  *  *  *  *  3  2  1 
 1  2  3  4  *  *  *  *  4  3  2  1 
 1  2  3  4  5  *  *  5  4  3  2  1 
 1  2  3  4  5  6  6  5  4  3  2  1 


```

```#include<stdio.h>
void main()
{
    int i,j,k;
    
    for(i=1; i<=6; i++){
        
       
        for(k=1; k<=i; k++){
            printf(" %d ",k);
        }

        for(j=1; j<=6-i; j++){
            printf(" * ");
        } 
          for(j=6-i; j>=1; j--){
            printf(" * ");
        }
        
          for(j=i; j>=1; j--){
            printf(" %d ", j);
        }
        
        printf("\n");
        
    }
}
```