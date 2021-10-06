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
![01](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/01.PNG)

## Optimization Approaches
- Generate and test: small input space, complex function
- Calculus: function has derivative, solvable = 0
- Network method: function has derivative, iteratively improve -> single optimum
- What if assumtion don't hold? **Randomized optimization**
	**big input space, complex function, no derivative (or hard to find), possibly many local optima**

- Methods:
    - Hill climbing:
        ![02](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/02.PNG)
        - Guess my word practice as an exmaple for hill climbing method. This game is suitable for hill climbing since it only have 1 global optimum.
            ![03](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/03.PNG)
        - Random restart hill climbing
            ![04](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/04.PNG)
            ![05](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/05.PNG)
    - Simulated Annealing
        - definition:
            ![06](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/06.PNG)
        - algorithm: **P(x, xt, T)**
            - for this probablity function help to decide how to make a move
            - the probability (current at x, and we are thinking to move to xt, and current temperature is T). 
                - If the fitness of the new point >= old point, make a move (hill climbing); 
                - else: calculate the value (e....) If two fitness value close to each other (diffrence close to zero), e0 ~ 1, make the move. If two fitness value very different, e0 ~ 0, no move.
                - ![07](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/07.PNG)
        - properties of simulated annealing
            ![08](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/08.PNG)
    - Genetic Algorithm (GA)
        - ![09](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/09.PNG)
        - ![10](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/10.PNG)
        - Example, crossover
            ![11](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/11.PNG)
## Summary
![12](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/12.PNG)

## MIMIC
- Mimic algorithms
    - only point, no structure: convey structure
    - unclear probability distribution: 
        - directly model distribution
        - successively refine model
    - ![13](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/13.PNG)
    - Pseudo code:
        ![14](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/14.PNG)
    - Estimate distribution
        ![15](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL11/15.PNG)