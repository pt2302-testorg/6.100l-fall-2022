---
content_type: page
description: 'All the videos and notes for Lecture 15: Recursion.'
draft: false
title: 'Lecture 15: Recursion'
uid: adcc2cba-7de5-4961-8a77-572b8b6210c9
---
**Topics:** Recursion: iteration vs. recursion, inductive reasoning

{{< resource uuid="15b66cf3-1510-4ee8-96ab-80c8c1eb98fe" >}}

## Lecture Notes

{{% resource_link "3341ae78-633c-4b15-93a9-d81d38189343" "Lecture 15: Recursion" %}}

{{% resource_link "67d1f1a7-8b02-41bc-a722-b81ed7d976d4" "Lecture 15 Code" %}}

## Readings

Ch 6.1

## Finger Exercise Lecture 15

Implement the function that meets the specifications below:

```python
def recur_power(base, exp):
    """
    base: int or float.
    exp: int >= 0

    Returns base to the power of exp using recursion.
    Hint: Base case is when exp = 0. Otherwise, in the recursive
    case you return base * base^(exp-1).
    """
    # Your code here  

# Examples:
print(recur_power(2,5)  # prints 32
```

{{% resource_link "4c6224af-c44d-4959-9639-a11ef9ef9caf" "6.100L Finger Exercises Lecture 15 Solutions" %}}