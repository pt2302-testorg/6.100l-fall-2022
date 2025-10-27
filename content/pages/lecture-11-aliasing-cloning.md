---
content_type: page
description: 'All of the videos and notes for Lecture 11: Aliasing, Cloning.'
draft: false
title: 'Lecture 11: Aliasing, Cloning'
uid: 86b85be7-2da6-43de-ae54-1996c5ee48c9
---
**Topics:** Aliasing and cloning, list comprehensions

{{< resource uuid="eb91c85b-7cb8-48d0-9b9a-85e9159554a7" >}}

## Lecture Notes

{{% resource_link "8c9a3907-5b33-40e6-acfd-b118e0a3ca5b" "Lecture 11: Aliasing, Cloning" %}}

{{% resource_link "f92561d1-e08d-4e23-a38d-4634e175fac8" "Lecture 11 Code" %}}

## Readings

Ch 5.3–5.5

## Finger Exercise Lecture 11

Implement the function that meets the specifications below:

```python
def remove_and_sort(Lin, k):
    """ Lin is a list of ints
        k is an int >= 0
    Mutates Lin to remove the first k elements in Lin and 
    then sorts the remaining elements in ascending order.
    If you run out of items to remove, Lin is mutated to an empty list.
    Does not return anything.
    """
    # Your code here  

# Examples:
L = [1,6,3]
k = 1
remove_and_sort(L, k)
print(L)   # prints the list [3, 6]
```

{{% resource_link "28d6b3b4-e5cd-4e6c-a556-076346f9e63b" "6.100L Finger Exercises Lecture 11 Solutions" %}}