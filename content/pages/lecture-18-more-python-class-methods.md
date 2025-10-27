---
content_type: page
description: 'All the videos and notes for Lecture 18: More Python Class Methods.'
draft: false
title: 'Lecture 18: More Python Class Methods'
uid: 7fe22bff-9a38-4536-8e45-a0dac3d7f2aa
---
**Topics:** Object Oriented Programming: dunder methods, examples

{{< resource uuid="67feac60-4f1e-4c08-b688-507c9f8b48e5" >}}

## Lecture Notes

{{% resource_link "897702c8-cb09-4dd5-a624-6efd7cbbe6d4" "Lecture 18: More Python Class Methods" %}}

{{% resource_link "a5834ad9-03f5-4743-9fcc-ceca0e5a9e0d" "Lecture 18 Code" %}}

## Readings

Ch 10.1

## Finger Exercise Lecture 18

Write the class according to the specifications below:

```python
class Circle():
    def __init__(self, radius):
        """ Initializes self with radius """
        # your code here

    def get_radius(self):
        """ Returns the radius of self """
        # your code here

    def __add__(self, c):
        """ c is a Circle object 
        Returns a new Circle object whose radius is 
        the sum of self and c's radius """
        # your code here

    def __str__(self):
        """ A Circle's string representation is the radius """
        # your code here
```

{{% resource_link "26e142cc-cd9b-4d03-a760-9cab2992f848" "6.100L Finger Exercises Lecture 18 Solutions" %}}