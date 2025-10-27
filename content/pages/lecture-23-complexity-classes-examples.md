---
content_type: page
description: 'All the videos and notes for Lecture 23: Complexity Classes Examples.'
draft: false
title: 'Lecture 23: Complexity Classes Examples'
uid: 8a9d842a-c8aa-49b1-97ff-54b302a2094b
---
**Topics:** String and List Examples, Analyzing Complexity, Search: indirection, linear search, bisection search

{{< resource uuid="7c42950b-dad5-4784-beb2-6c66c926eb81" >}}

## Lecture Notes

{{% resource_link "9647bcb6-b55e-4c1b-b891-044b92008bc0" "Lecture 23: Complexity Classes Examples" %}}

{{% resource_link "e2a660b6-247f-4924-9ec5-e68bd168c267" "Lecture 23 Code" %}}

## Readings

Ch 12.1

## Finger Exercise Lecture 23

Question 1: Choose the worst case asymptotic order of growth (upper and lower bound) for the following function. Assume `n = a`.

```python
def running_product(a):
    """ a is an int """
    product = 1
    for i in range(5,a+5):
        product *= i
        if product == a:
            return True
    return False
```

Question 2: Choose the worst case asymptotic order of growth (upper and lower bound) for the following function. Assume `n = len(L)`.

```python
def tricky_f(L, L2):
    """ L and L2 are lists of equal length """
    inL = False
    for e1 in L:
        if e1 in L2:
            inL = True
    inL2 = False
    for e2 in L2:
        if e2 in L:
            inL2 = True
    return inL and inL2
```

Question 3: Choose the worst-case asymptotic order of growth (upper and lower bound) for the following function.

```python
def sum_f(n):
    """ n > 0 """
    answer = 0
    while n > 0:
        answer += n%10
        n = int(n/10)
    return answer
```

{{% resource_link "f0af762d-78de-4fc0-869a-63a9a2e87296" "6.100L Finger Exercises Lecture 23 Solutions" %}}

## Recitation 10

Recitations were smaller sections that reviewed the previous lectures. Files contain recitation notes and worked examples in code.

{{% resource_link "d5edab93-2da6-4eb0-be2f-c7f9264f0a79" "Recitation 10 Notes and Code" %}}