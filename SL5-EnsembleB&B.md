# Ensemble Learning: Boosting
- Emsemble learning characteristic:
    - take some simple rules
    - combine simple rule to complex rule
    - Spam email example:
    ![01](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL5/01_ENSEMBLE.PNG)
    - Why look at subset of data instead of all data?
        - If we look at all data, it is hard to generate **simple rule**.
        - this is related to overfitting as well.
- Implementation:
    - Simple way:
        - subset of data: select randomly (uniformly random)
        - combine: average each subset
        -  ![02](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL5/02_example.PNG)
        - For example: **Bagging**  (bootstrap aggregation)
            - Taking subsets is better than learn all data together:
                - prevent overfitting
                - average out the variances and differences
            - ![03](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL5/03_example_housedata.PNG)
    - **Boosting**
        - ![04](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL5/04_bagging.PNG)
        - weak learner: A learner, no matter wht the distrbituino is over your data, will do better than chance when it tries to elarn labels on that data.  
            - What is does better than chance? no matter the data distribution, you are always going to have an **error rate** that's **less then 1/2**
        - ![05](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL5/05.PNG)
        - ![07](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL5/07.PNG)
        - Example of combine simple model to a good one:
            - ![08](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL5/08.PNG)
            - ![09](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL5/09.PNG)
## Summary
![summary](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL5/10.PNG)
       

