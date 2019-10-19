---
title: Number Pattern 1
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 17
---


## Pattern 17

```
1     1
 2   2 
  3 3  
   4   
  5 5  
 6   6 
7     7



```

```
#include<stdio.h>
void main(){
    int i,j;
    for(i=1;i<=7; i++){
        for(j=1; j<=7; j++ ){
            if(i==j){
                printf("%d",j);
            }
            else if(i==8-j){
                printf("%d",i);
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