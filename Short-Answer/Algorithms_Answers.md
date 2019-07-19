Add your answers to the Algorithms exercises here.

```
a)  a = 0
    while (a < n * n * n):
      a = a + n * n
```
above is a O(n) level Algorithems

b)  sum = 0
    for i in range(n):
      i += 1
      for j in range(i + 1, n):
        j += 1
        for k in range(j + 1, n):
          k += 1
          for l in range(k + 1, 10 + k):
            l += 1
            sum += 1
```
above is a O(n^4) level algorithems

c)  def bunnyEars(bunnies):
      if bunnies == 0:
        return 0

      return 2 + bunnyEars(bunnies-1)

above is a O(n) level algorithems 

Suppose that you have an _n_-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor _f_ or higher, and doesn't get broken if dropped off a floor less than floor _f_. Devise a strategy to determine the value of _f_ such that the number of dropped eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode and give the runtime complexity of your solution.


either keep all the eggs at the Floor level lower than _f_ or don't drop the eggs, also if I have to go above _f_ level, need to make sure I have a bigger container that will retain all the eggs.