# Primes Walk

The Primes Walk is an exploration of patterns found in prime numbers, and various ways to plot these findings.

## Primes Walk Algorithm

```python
# The algorithm takes as input the positive integers
# Initial plotter heading = 0 degrees (pointing right on the page)
limit = 10000
n = 1
while (n <= limit)
  if n is composite, Move 1 unit horizontally along current heading
  if n is prime, Move Up 1, turn 90 degrees left, then Move 1 on this heading
  n = n + 1
```
Plot the lines and each point (i.e. the plotter pen stays down theh whole time).

### Notes
I wrote the original in Java back in the 2000's when I was learning OO programming.
I no longer have that version, but I may rewrite this in Python one day.