# homework.


# re: firsthomework.ipynb
Solving `x² + 5x + 6 = 0` three separate times, entirely on a phone, at increasing levels of consciousness.

## The Development Environment

- **Hardware:** phone
- **Keyboard:** phone keyboard
- **IDE:** Google Colab, viewed through a phone
- **Emotional state:** deteriorating (see commit history / cell comments)

## What's in here

| Task | Approach | Result |
|---|---|---|
| 1.1 | Manual quadratic formula, typed by hand | `-2` |
| 1.2 | Manual quadratic formula again, just to be sure | `-2` (still) |
| 1.3 | `install.packages("QuadRoot")` because typing `-sqrt()` a second time felt like too much | `-2` and `-3`, and it even writes you a sentence about it |

## Key Findings

- The quadratic formula has not changed since task 1.1.
- Confirming this in task 1.2 did not change it either.
- Installing an entire R package to get the second root was, in fact, less typing than writing `x_minus <- (-b - sqrt(...)) / (2*a)`. This is either optimal engineering or a cry for help. Unclear.
- One code cell contains only the comment `#i am so sleepy`. It was left in as a scientific record.

## Reproducing These Results

```r
a <- 1; b <- 5; c <- 6
disc <- sqrt(b^2 - 4*a*c)
c((-b + disc) / (2*a), (-b - disc) / (2*a))
```

Two lines. No install. No phone required, but not prohibited either.

## Disclaimer

Written entirely via touchscreen. Please clap.
