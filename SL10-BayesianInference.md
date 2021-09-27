# Bayesian Inference
## Intro to Bayesian Inference
- Representing and reasoning with probabilities. (Bayesian network)
- Joint distribution
    - Example:
        - ![01](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL10/01.PNG)
        - adding attribute: factor it!
        ![02]()
    - conditional independent
        - X is conditionally indepent to y given z:
        ![03](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL10/03.PNG)
        - Example
        ![04](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL10/04.PNG)
            - 1) = 0.04/0.4
            - 2) = 0.03/0.3
            - **Storm is conditionally independent of thunder given lightning**
- Belief network
    - Example:
    ![05](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL10/05.PNG)
        - P(L|S) = 0.25/(0.25+0.4) = 0.385
        - p(Th|L) = 0.2/0.25 (storm is independent)
- Sampling form the Joint distribution
    ![06]()