---
content_type: page
description: 'All the videos and notes for Lecture 20: Fitness Tracker Object-Oriented
  Programming Example.'
draft: false
title: 'Lecture 20: Fitness Tracker Object-Oriented Programming Example'
uid: 8508df66-d20e-4944-b70a-cbb517291269
---
**Topics:**  Inheritance: more examples

{{< resource uuid="d37d2554-11ae-4452-b482-b137f631b485" >}}

## Lecture Notes

{{% resource_link "37891806-f719-48e6-ae08-b579feb8bc30" "Lecture 20: Fitness Tracker Object-Oriented Programming Example" %}}

{{% resource_link "33387e15-3290-4a37-8e36-3112b50a5cc8" "Lecture 20 Code" %}}

## Readings

Ch 10.4

## Finger Exercise Lecture 20

In this problem, you will implement two classes according to the specification below: one `Container` class and one `Queue` class (a subclass of `Container`).     

Our `Container` class will initialize an empty list. The two methods we will have are to calculate the size of the list and to add an element. The second method will be inherited by the subclass. We now want to create a subclass so that we can add more functionality -- the ability to remove elements from the list. A `Queue` will add elements to the list in the same way, but will behave differently when removing an element.

A queue is a first-in, first-out data structure. Think of a store checkout queue. The customer who has been in the line the longest gets the next available cashier. When implementing your `Queue` class, you will have to think about which end of your list contains the element that has been in the list the longest. This is the element you will want to remove and return.

```python
class Container(object):
    """
    A container object is a list and can store elements of any type
    """
    def __init__(self):
        """
        Initializes an empty list
        """
        self.myList = []

    def size(self):
        """
        Returns the length of the container list
        """
        # Your code here

    def add(self, elem):
        """
        Adds the elem to one end of the container list, keeping the end
        you add to consistent. Does not return anything
        """
        # Your code here

class Queue(Container):
    """
    A subclass of Container. Has an additional method to remove elements.
    """
    def remove(self):
        """
        The oldest element in the container list is removed
        Returns the element removed or None if the stack contains no elements
        """
        # Your code here
```

{{% resource_link "38c103a5-b6c0-4086-9308-496d1448aaa1" "6.100L Finger Exercises Lecture 20 Solutions" %}}

## Problem Set 5

{{% resource_link "6abf583f-c3f4-4aac-afff-0a844129a38e" "Problem Set 5" %}}

{{% resource_link "d7498336-87b2-4cc9-bf47-1ee9540822cd" "Problem Set 5 Code" %}}

## Recitation 9

Recitations were smaller sections that reviewed the previous lectures. Files contain recitation notes and worked examples in code.

{{% resource_link "33c3d16a-3969-4da6-87e9-b372345b2708" "Recitation 9 Notes and Code" %}}