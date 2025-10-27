---
content_type: page
description: 'All the videos and notes for Lecture 7: Decomposition, Abstraction,
  Functions.'
draft: false
title: 'Lecture 7: Decomposition, Abstraction, Functions'
uid: 91ce0099-2767-49c3-8d73-27c2f141093e
---
**Topics:** Functions: decomposition, abstraction, specifications

{{< resource uuid="0a52b5d2-0cb4-4271-b63d-86a599807c98" >}}

## Lecture Notes

{{% resource_link "e9e748ad-4e91-440c-a94d-d593edbc20aa" "Lecture 7: Decomposition, Abstraction, Functions" %}}

{{% resource_link "8ac8cd65-1068-4a4d-81db-cdf190435c23" "Lecture 7 Code" %}}

## Readings

Ch 4.1–4.2

## Finger Exercise Lecture 7

Question 1: Implement the function that meets the specifications below:

```python
def eval_quadratic(a, b, c, x):
    """
    a, b, c: numerical values for the coefficients of a quadratic equation
    x: numerical value at which to evaluate the quadratic.
    Returns the value of the quadratic a×x² + b×x + c.
    """
    # Your code here

# Examples:    
print(eval_quadratic(1, 1, 1, 1)) # prints 3
```

Question 2: Implement the function that meets the specifications below:

```python
def two_quadratics(a1, b1, c1, x1, a2, b2, c2, x2):
    """
    a1, b1, c1: one set of coefficients of a quadratic equation
    a2, b2, c2: another set of coefficients of a quadratic equation
    x1, x2: values at which to evaluate the quadratics
    Evaluates one quadratic with coefficients a1, b1, c1, at x1.
    Evaluates another quadratic with coefficients a2, b2, c2, at x2.
    Prints the sum of the two evaluations. Does not return anything.
    """
    # Your code here

# Examples:    
two_quadratics(1, 1, 1, 1, 1, 1, 1, 1) # prints 6
print(two_quadratics(1, 1, 1, 1, 1, 1, 1, 1)) # prints 6 then None
```

{{% resource_link "a92d96d0-35cc-4c49-a331-55d9931cbf99" "6.100L Finger Exercises Lecture 7 Solutions" %}}

## Recitation 3

Recitations were smaller sections that reviewed the previous lectures. Files contain recitation notes and worked examples in code.

{{% resource_link "c4d6d77f-1a02-41fa-ac4b-c15f73146304" "Recitation 3 Notes and Code" %}}