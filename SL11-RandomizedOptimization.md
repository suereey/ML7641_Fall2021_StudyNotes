# Randomized Optimization

## Optimization
- input space X
- objectvie fnction (fitness function) F:X -> R (score)
- Goal: find x*∈X s.t f(x*)=maxf(x)
	- find the x* such that the fitness value for x* is equal to or as close as possible to the maximum possible value.
- Find the best:
	- process control
	- route finding
	- root finding
	- neural network x is weights minize error
	- decision tree
- Example of optimization
![01]()

## Optimization Approaches
- Generate and test: small input space, complex function
- Calculus: function has derivative, solvable = 0
- Network method: function has derivative, iteratively improve -> single optimum
- What if assumtion don't hold? **Randomized optimization**
	**big input space, complex function, no derivative (or hard to find), possibly many local optima**

- Methods:
    - Hill climbing:
        ![02]()
        - Guess my word practice as an exmaple for hill climbing method. This game is suitable for hill climbing since it only have 1 global optimum.
            ![03]()
        - Random restart hill climbing
            ![04]()
            ![05]()
    - Simulated Annealing