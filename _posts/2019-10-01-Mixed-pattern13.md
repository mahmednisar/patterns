---
title: Mixed Pattern 13
tags: [Mixed Pattern ]
style: fill
color: secondary
description: Mixed Pattern 13

---


## Pattern 13

```
 6  5  4  3  2  1  2  3  4  5  6 
 *  6  5  4  3  2  1  3  4  5  6 
 *  *  6  5  4  3  2  1  4  5  6 
 *  *  *  6  5  4  3  2  1  5  6 
 *  *  *  *  6  5  4  3  2  1  6 
 *  *  *  *  *  6  5  4  3  2  1 


```

```
#include<stdio.h>
void main()
{
    int i,j,k;
    
    for(i=1; i<=6; i++){
        
       
        for(k=0; k<i-1; k++){
            printf(" * ");
        }

       
        for(j=6; j>=1; j--){
            printf(" %d ",j);
        }
          for(j=i+1; j<=6; j++){
            printf(" %d ",j);
        }
         
        printf("\n");
        
    }
}

```