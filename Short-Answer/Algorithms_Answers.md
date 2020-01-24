#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
O(n) because a is incremented linearly by n*n with respect to the input n. The loop stops running at n steps.

b)
O(n log n) because the for loop runs on O(n), and the while loop runs on O(log n) since j is being incremented twice as quickly, meaning the runtime grows at a slower rate. Combining the two runtimes together, the overall time complexity becomes O(n log n)

c)
O(n) because the function is called recursively based on 'bunnies' until the base case is reached. Each call is incremented by 2, which makes it linear with respect to 'bunnies'


## Exercise II

I would implement a binary search to find the value of f. Use n/2 to determine if the egg gets broken or not. If it gets broken, use the binary search for the lower half of n, or use the higher half of n if it does not break. Continue binary search until there are only 2 floors left, one of which should be the true value of f where the egg doesn't break.  

The floors should be sorted and the time complexity would be O(Log n) since the search interval is decreasing with every iteration.