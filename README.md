# data science with R.


# re: lecture 02 practice (formerly known as firsthomework.ipynb)
Solving `x² + 5x + 6 = 0` three separate times, entirely on a cell phone, at increasing levels of consciousness?

# development 

- Hardware: phone
- Keyboard phone keyboard
- Google Colab, viewed through a phone
- ignore.. a lot of the commit history / cell comments 

# What happened?

| task | approach | result |
|---|---|---|
| 1.1 | Manual quadratic formula, typed by hand | `-2` |
| 1.2 | Manual quadratic formula again, just to be sure | `-2` (still) |
| 1.3 | `install.packages("QuadRoot")` because typing `-sqrt()` a second time felt like too much | `-2` and `-3`, and it even writes you a sentence about it |

# my findings include

- The quadratic formula has not changed since task 1.1.
- Confirming this in task 1.2 did not change it either.
- Installing an entire R package to get the second root was, in fact, less typing than writing `x_minus <- (-b - sqrt(...)) / (2*a)`. This is neither optimal engineering it’s more of a cry for help
- One code cell contains only the comment ‘#i am so sleepy’ and it was left in as a scientific record.

#this 

```r
a <- 1; b <- 5; c <- 6
disc <- sqrt(b^2 - 4*a*c)
c((-b + disc) / (2*a), (-b - disc) / (2*a))
```

, 


