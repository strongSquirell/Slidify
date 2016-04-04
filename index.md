---
title       : Quadratic Equation Solver
subtitle    : Developing Data Products Project
author      : Alina Rusina
job         : student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is a quadratic equation

A quadratic equation (from the Latin quadratus for "square") is any equation having the form

$ax^2+bx+c=0$

where x represents an unknown, and a, b, and c represent known numbers such that a is not equal to 0. If a = 0, then the equation is linear, not quadratic.

--- 

## Input

We solve a quadratic equation over the field of real or complex numbers.

User should choose a system(real, complex) and specify coefficients a, b, c.

Default values are system = "real", a = 1, b = 2, c = 1.  

---

## Output

If user choose real numbers and discriminant < 0, output is "Wrond input",
in all other cases application will compute 2 real roots.

If complex system is chosen roots is always calculated.

Output with defalt values is 1 1

---

## Implementation

We use function findRoots which takes strinf for system and 3 numerics for coefficients.


Lets try it

```r
findRoots("real", 1, 7, -12)
```

```
## [1]  1.424429 -8.424429
```
---
