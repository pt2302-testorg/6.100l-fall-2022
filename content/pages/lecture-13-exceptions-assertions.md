---
content_type: page
description: 'All the videos and notes for Lecture 13: Exceptions, Assertions.'
draft: false
title: 'Lecture 13: Exceptions, Assertions'
uid: 0a8e2220-17b1-4d76-b5e1-919a4c70948c
---
**Topics:** Exceptions, assertions

{{< resource uuid="f95261f3-f644-4ee9-8a06-6a0a999a39cc" >}}

## Lecture Notes

{{% resource_link "66e35bdc-370a-482f-a7ab-e39921067289" "Lecture 13: Exceptions, Assertions" %}}

{{% resource_link "13f99432-07b9-431f-8666-d6d57e0811a1" "Lecture 13 Code" %}}

## Readings

Ch 9

## Finger Exercise Lecture 13

Implement the function that meets the specifications below:

```python
def sum_str_lengths(L):
    """
    L is a non-empty list containing either: 
    * string elements or 
    * a non-empty sublist of string elements
    Returns the sum of the length of all strings in L and 
    lengths of strings in the sublists of L. If L contains an 
    element that is not a string or a list, or L's sublists 
    contain an element that is not a string, raise a ValueError.
    """
    # Your code here  

# Examples:
print(sum_str_lengths(["abcd", ["e", "fg"]]))  # prints 7
print(sum_str_lengths([12, ["e", "fg"]]))      # raises ValueError
print(sum_str_lengths(["abcd", [3, "fg"]]))    # raises ValueError
```

{{% resource_link "81bcae1c-892a-4334-b927-7a72d60a1476" "6.100L Finger Exercises Lecture 13 Solutions" %}}