---
content_type: page
description: 'All the videos and notes for Lecture 14: Dictionaries.'
draft: false
title: 'Lecture 14: Dictionaries'
uid: 92027d09-a6a3-4a8e-b356-393474f6dd61
---
**Topics:** Dictionaries: keys, values, mutability, iteration over a dict, examples

{{< resource uuid="c651f955-1cbf-4c6c-9311-393de1bea7f0" >}}

## Lecture Notes

{{% resource_link "09cc8ba7-41a4-4a04-ad76-0da3be0b235c" "Lecture 14: Dictionaries" %}}

{{% resource_link "17e4ba71-fc0a-477d-b067-0b693cff31b2" "Lecture 14 Code" %}}

## Readings

Ch 5.7

## Finger Exercise Lecture 14

Question 1: Implement the function that meets the specifications below:

```python
def keys_with_value(aDict, target):
    """
    aDict: a dictionary
    target: an integer or string
    Assume that keys and values in aDict are integers or strings.
    Returns a sorted list of the keys in aDict with the value target.
    If aDict does not contain the value target, returns an empty list.
    """
    # Your code here  

# Examples:
aDict = {1:2, 2:4, 5:2}
target = 2   
print(keys_with_value(aDict, target)) # prints the list [1,5]
```

Question 2: Implement the function that meets the specifications below:

```python
def all_positive(d):
    """
    d is a dictionary that maps int:list
    Suppose an element in d is a key k mapping to value v (a non-empty list).
    Returns the sorted list of all k whose v elements sums up to a 
    positive value.
    """
    # Your code here  

# Examples:
d = {5:[2,-4], 2:[1,2,3], 1:[2]}
print(all_positive(d))   # prints the list [1, 2]
```

{{% resource_link "59997c48-dfd5-41e8-a9ff-403d43eec3ad" "6.100L Finger Exercises Lecture 14 Solutions" %}}

## Recitation 7

Recitations were smaller sections that reviewed the previous lectures. Files contain recitation notes and worked examples in code.

{{% resource_link "d5c0d4c2-7ff7-4c76-a2a5-01a330bbcbad" "Recitation 7 Notes and Code" %}}