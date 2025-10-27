---
content_type: page
description: 'All the videos and notes for Lecture 19: Inheritance.'
draft: false
title: 'Lecture 19: Inheritance'
uid: 9b3ecf05-86be-45dd-b64b-0290f5fa4a46
---
**Topics:**  Inheritance: hierarchies, subclasses, using inherited methods, examples

{{< resource uuid="d8d10831-d0bc-4745-8692-1278df76bb9a" >}}

## Lecture Notes

{{% resource_link "19848ab8-527a-4ee8-bc89-09dbc3be9650" "Lecture 19: Inheritance" %}}

{{% resource_link "babe5f97-af1e-4895-87d3-12d8bd2a6bfd" "Lecture 19 Code" %}}

## Readings

Ch 10.2

## Finger Exercise Lecture 19

In this problem, you will implement two classes according to the specification below: one `Container` class and one `Stack` class (a subclass of `Container`).

Our `Container` class will initialize an empty list. The two methods we will have are to calculate the size of the list and to add an element. The second method will be inherited by the subclass. We now want to create a subclass so that we can add more functionality—the ability to remove elements from the list. A `Stack` will add elements to the list in the same way, but will behave differently when removing an element.

A stack is a last-in, first-out data structure. Think of a stack of pancakes. As you make pancakes, you create a stack of them with older pancakes going on the bottom and newer pancakes on the top. As you start eating the pancakes, you pick one off the top so you are removing the newest pancake added to the stack. When implementing your `Stack` class, you will have to think about which end of your list contains the element that has been in the list the shortest amount of time. This is the element you will want to remove and return.

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

class Stack(Container):
    """
    A subclass of Container. Has an additional method to remove elements.
    """
    def remove(self):
        """
        The newest element in the container list is removed
        Returns the element removed or None if the queue contains no elements
        """
        # Your code here
```

{{% resource_link "3f3b7c7e-d302-482b-978d-c9024c9256da" "6.100L Finger Exercises Lecture 19 Solutions" %}}