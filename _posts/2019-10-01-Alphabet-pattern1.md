---
title: Alphabet Pattern 1
tags: [Alphabet Pattern ]
style: fill
color: secondary
description: Alphabet Pattern 1
---


## Pattern 1

```
A
BB
CCC
DDDD
EEEEE

```

```
#include <stdio.h>
 
int main ()
{
char ch = 'A';
        for (int i = 1; i <= 5; i++) {
            for (int j = 1; j <= i; j++) {
                printf("%c", ch);
            }
            ch++;
            printf("\n");
        }
  return 0;
}
 ```