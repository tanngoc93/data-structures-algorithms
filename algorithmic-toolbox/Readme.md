- Document
  - [week1_programming_challenges.pdf](files/week1_programming_challenges.pdf)
  - [week2_algorithmic_warmup.pdf](files/week2_algorithmic_warmup.pdf)

## Asymptotic notation:
The key idea is that low-level run time analysis can result in confounding factors that multiply runtimes by a (large) constant, so we seek to measure runtime in a way that ignores constant multiples.
`log n < sqrt(n) < n < n log n < n^2 < 2^n`

## Big-O notation
Warnings when using Big-O:

Using Big-O loses important information about constant multiples.
Big-O is only asymptotic (in the sense that it only tells us what happens when n is large, but nothing about the runtime given a specific input).
