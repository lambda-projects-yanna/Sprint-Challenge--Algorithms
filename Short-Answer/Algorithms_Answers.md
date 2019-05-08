Add your answers to the Algorithms exercises here.

a) Loop runs as long as (n*n +a) < n*n*n
    so when a = n, we have (n*n*n), which would break the loop.
so the runtime is O(n) at most. 

b) The first loop will run n times.
    The second loop will run to n.
    The third loop will run to n.
    The fourth loop will run to 10+k elements, where k = n at most, so this will run at most n times.
so the runtime is O(n^4) at most.
n^3

c) this runs at most 2(bunnies) times 
so runtime is O(2n) at most
actually n

d) we can go to the middle floor of the building and check if an egg breaks from there. If yes, we drop an egg from each floor below midpoint until we find one where it does not break.
If the egg doesn't break at the middle floor, we drop an egg from each floor above the base case until we find a floor where the egg does break.

if n = stories in building, and we had a recursive algorithm where the function called itself with input (n-1) as needed, the runtime would be O(2^n/2) at most, 
taking away the constant, O(2^n)



