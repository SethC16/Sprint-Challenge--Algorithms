#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n), the loop runs n number of times.


b) O(n log n), outer loop runs n number of times and inner loop runs (i+1) number of times.


c) O(n), the function is called it will recursively for n number of times until reaching zero and exiting with the return of 0

## Exercise II
- Divide the maximun number of floors by two to get the middle floor.
- Go to middle floor and drop egg
- if egg breaks, then take the middle floor and divide by two
- this becomes the new middle floor (bst)
- Repeat dropping egg until egg does not break
- Once floor has been found to not break egg, check n+1 to the next floor      until you reach edge of f

- solution should be 0(log n)


