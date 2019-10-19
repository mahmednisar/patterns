---
title: Number Pattern 16
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 16
---


## Pattern 16

```
1     1
 1   1 
  1 1  
   1   
  1 1  
 1   1 
1     1



```

```
#include<stdio.h>
void main(){
    int i,j;
    for(i=1;i<=7; i++){
        for(j=1; j<=7; j++ ){
            if(i==j||i==8-j){
                printf("1");
            }
            else
            {
                printf(" ");
            }
            
        }
        printf("\n");
    }
}
```