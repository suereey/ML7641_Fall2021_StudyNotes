# Kernel Methods and Support Vector Machines(SVMs)
## Find the best line:
- Linear classifier: y = wTx + b
    - Even in multiple dimension hyperplane
    -  ![00]()
    - **Decision Boundry** 0 = wTx + b
    - Quiz: what is the distance of the two planes?
        - ![01]()
        - Basically, this result means, sbustract the two equations. It is the difference of x1 and x2 projected on the normlized w vector.
        - Maximize the distance between x1 and x2 by varing w. **Find the parameter of the hyperplane that maximize the distance ("margin" part in the equation), while still consistent with the data.