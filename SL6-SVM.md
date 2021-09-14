# Kernel Methods and Support Vector Machines(SVMs)
## Find the best line:
- Linear classifier: y = wTx + b
    - Even in multiple dimension hyperplane
    -  ![00](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL6/00.PNG)
    - **Decision Boundry** 0 = wTx + b
    - Quiz: what is the distance of the two planes?
        - ![01](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL6/01.PNG)
        - Basically, this result means, sbustract the two equations. It is the difference of x1 and x2 projected on the normlized w vector.
        - Maximize the distance between x1 and x2 by varing w. **Find the parameter of the hyperplane that maximize the distance ("margin" part in the equation), while still consistent with the data.
## SVM: What are are trying to solve
- instead of doing maximum, do minimum, them convert the problem into quatratic programming problem, which has a particular form. (maximize the alpha function)
    - ![02](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL6/02.PNG)
- the data points for which the corresponding alpha is non-zero, those are support vectors.
    - ![03]()