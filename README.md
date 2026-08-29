
## re: lecture 02 practice (formerly known as firsthomework.ipynb)
Solving `x² + 5x + 6 = 0` three separate times, entirely on a cell phone, at increasing levels of consciousness?


# what I used 

- Hardware: phone
- Keyboard phone keyboard
- Google Colab, viewed through a phone
- ignore.. a lot of the commit history / cell comments 

# What happened?

| task | approach | result |
|---|---|---|
| 1 | Manual quadratic formula, typed by hand | `-2` |
| 2 | Manual quadratic formula again, just to be sure | `-2` (still) |
| 3 | `install.packages("QuadRoot")` because typing `-sqrt()` a second time felt like too much | `-2` and `-3`, and it even writes you a sentence about it |

# my findings include

- The quadratic formula has not changed since task 1.
- Confirming this in task 2 did not change it either.
- Installing an entire R package to get the second root was, in fact, less typing than writing `x_minus <- (-b - sqrt(...)) / (2*a)`. This is neither optimal engineering it’s more of a cry for help
-  ‘i'm so sleepy’ and it was left in

## re lecture 02 CLEANED

# i fully cleaned from all prior reformatting metadata.


# task 1: define

`a <- 1`
`b <- 5`
`c <- 6`

# task 2: compute

`x_plus <- (-b + sqrt(b^2 - 4 * a * c)) / (2 * a)`
`x_plus`
`[1] -2`

# task 3: install Qdrt package

` install.packages("QuadRoot")`
`Installing package into ‘/usr/local/lib/R/site-library’`
` (as ‘lib’ is unspecified)`

# task 4: verify

`QuadRoot::QuadRoot(c(a, b, c))`
`[1] "The two x-intercepts for the quadratic equation are -2.0000 and -3.0000." `







