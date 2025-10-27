---
content_type: page
description: 'All the videos and notes for Lecture 8: Functions as Objects.'
draft: false
title: 'Lecture 8: Functions as Objects'
uid: a6dab17d-78aa-452d-a1e2-5e8293e961aa
---
**Topics:** Functions: environments, scope, functions as objects

{{< resource uuid="675dbf02-ed30-4bc9-b714-859e5c51dbb6" >}}

## Lecture Notes

{{% resource_link "804254c0-f074-4249-ae47-156b0671dee2" "Lecture 8: Functions as Objects" %}}

{{% resource_link "9f88e15c-6f61-453e-b1c4-2418e3365824" "Lecture 8 Code" %}}

## Readings

Ch 4.3–4.6

## Finger Exercise Lecture 8

Implement the function that meets the specifications below:

```python
def same_chars(s1, s2):
    """
    s1 and s2 are strings
    Returns boolean True is a character in s1 is also in s2, and vice 
    versa. If a character only exists in one of s1 or s2, returns False.
    """
    # Your code here

# Examples:
print(same_chars("abc", "cab"))     # prints True
print(same_chars("abccc", "caaab")) # prints True
print(same_chars("abcd", "cabaa"))  # prints False
print(same_chars("abcabc", "cabz")) # prints False
```

{{% resource_link "ec506a8a-6a65-4f12-a742-c0f24c666ee0" "6.100L Finger Exercises Lecture 8 Solutions" %}}