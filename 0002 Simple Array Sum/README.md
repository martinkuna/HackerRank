# 0002 [Simple Array Sum](https://www.hackerrank.com/challenges/simple-array-sum/problem)

Given an array of integers, find the sum of its elements.

## Input Format

The first line contains an integer, n, denoting the size of the array.

The second line contains n space-separated integers representing the array's elements.

## Output Format

Print the sum of the array's elements as a single integer.

## Sample Input

6

1 2 3 4 10 11

## Sample Output

31

## Explanation

We print the sum of the array's elements: 1 + 2 + 3 + 4 + 10 + 11 = 31

## C

```c
#include <math.h>
#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <assert.h>
#include <limits.h>
#include <stdbool.h>

int simpleArraySum(int n, int ar_size, int* ar) {
    // Complete this function
}

int main() {
    int n;
    scanf("%i", &n);
    int *ar = malloc(sizeof(int) * n);
    for(int ar_i = 0; ar_i < n; ar_i++){
       scanf("%i",&ar[ar_i]);
    }
    int result = simpleArraySum(n, n, ar);
    printf("%d\n", result);
    return 0;
}
```
