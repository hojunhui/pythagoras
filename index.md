---
title       : Finding the Longest Side of a Triangle
subtitle    : 
author      : Jun Hui Ho
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Snapshot
![width](screenshot.png)

--- .class #id 

## Overview
This program calculate the length of the longest side of a right-angled triangle from the lengths of the other two sides, based on Pythagoras Theorem.

$$c = \sqrt{a^2 + b^2}$$

where a, b and c are the 3 sides of a triangle, out of which c is the longest side.

---

## Program Computations

```r
a <- 3
b <- 4
c <- sqrt(a^2 + b^2)
c
```

```
## [1] 5
```

---

## Summary
# Advantages
- fast
- convenient
- simple

# Drawbacks
- limited to right-angled triangles only


