---
title: Number Pattern 19
tags: [Number Pattern ]
style: fill
color: secondary
description: Number Pattern 19
---


## Pattern 19

```
1 
2 7 
3 8 12 
4 9 13 16 
5 10 14 17 19 
6 11 15 18 20 21 


```

```
void main()
{
    int i,j,k,n=6;

    for(i=1;i<=n;i++)
    {
        k=i;
        for(j=1;j<=i;j++)
        {
            printf("%d ",k);
            k=k+(n-j);
        }
        printf("\n");
    }
}
```