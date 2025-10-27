---
content_type: page
description: 'All the videos and notes for Lecture 17: Python Classes.'
draft: false
title: 'Lecture 17: Python Classes'
uid: 4e60fce2-a5eb-4826-adef-d82950712b8f
---
**Topics:** Object Oriented Programming: data abstraction, class def, class instances, methods

{{< resource uuid="b02bc0f0-47c5-40c9-8508-bf0448367f5d" >}}

## Lecture Notes

{{% resource_link "e6ed8bbf-10e8-4e30-8f55-7304ad055838" "Lecture 17: Python Classes" %}}

{{% resource_link "4546213e-044c-4ec3-b829-de2ad782b289" "Lecture 17 Code" %}}

## Readings

Ch 10.1

## Finger Exercise Lecture 17

Write the class according to the specifications below:

```python
class Circle():
    def __init__(self, radius):
        """ Initializes self with radius """
        # your code here

    def get_radius(self):
        """ Returns the radius of self """
        # your code here

    def set_radius(self, radius):
        """ radius is a number
        Changes the radius of self to radius """
        # your code here

    def get_area(self):
        """ Returns the area of self using pi = 3.14 """
        # your code here

    def equal(self, c):
        """ c is a Circle object
        Returns True if self and c have the same radius value """
        # your code here

    def bigger(self, c):
        """ c is a Circle object
        Returns self or c, the Circle object with the bigger radius """
        # your code here
```

{{% resource_link "5cbf72a3-ef9a-40f8-b348-6cd9015e8ca9" "6.100L Finger Exercises Lecture 17 Solutions" %}}