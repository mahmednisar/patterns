---
title: Number Pattern 18
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 18
---


## Pattern 18

```
  1 
  2   7 
  3   8  12 
  4   9  13  17 
  5  10  14  18  22 
  6  11  15  19  23  27 


```

```
#include<stdio.h>
void main(){
    int i,j,d;
    for(i=1;i<=6;i++){
        int n=5,d=5;;
        for(j=1;j<=i; j++){
            if(j==1){
                printf(" %2d ",i);
            }
            else
            {
               d=i+d;
                printf(" %2d ",d);
                
              d=d+n-i-1;
            }
            
        }
        printf("\n");
    }
}
```