# Feature Transformation

## Intro
![01](https://github.com/suereey/ML7641_Fall2021_StudyNotes/blob/main/Screenshot/UL4/1.PNG)
- feature selection is a subset of feature transformation
    - feature selection: prepocessing, taking a subset of features
    - feature transformation: more powerful, can be arbitraty preprocessing. not just sth that goes from a set to a subset, but linear combnations of original features
- Why we do feature transformation?
    - Problem example:
    ![02](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL4/2.PNG)
    ![03](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL4/3.PNG)
        - note: CAR example in slides. [moreinfo](https://en.wikipedia.org/wiki/CAR_and_CDR)

## Linear transformation algorithm
- Principla compoenets analysis
![04](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL4/4.PNG)
    - gloabal algorithm. global -> all directions, all new features find a big global constraint, namely that they must be mutually orthogonal
    - can be proved, pca gives best reconstruction. reconstruct -> given you all features, you can reconstruct all of the original data