# Decision Tree

## Supervised learning include Classification and Regression
- Difference between Classification and Regression
- Is it Classificatino or Regression problem?
    - Depends on the output. 
    - The output is discrete: Regression
    - The output is not discrete: Classification

## Classification learning
- Keywords
    - Instances: input
    - Concept: function (maps input to output)
    - Target concept: actual answer (the things we are trying to find)
    - Hypothesis (class): all the functions that could think about
    - Sample: training set
    - Candidate: a concept that you think might be the target concept
    - Testing: testing set
- Decision tree expression:
    - And: ![andexp](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/screenshot/1_andexpression.PNG)
    - Or: ![Orexp](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/screenshot/2_orexpression.PNG)
    - XOr (either one): ![xorexp](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/screenshot/3_xor.PNG)
    - Try to have OR problem instead of XOR (complext)
        - ![complexity](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/screenshot/4_linearexponential.PNG)

- Algorithm: ID3
    - Select best A (attribute) based on information gain.
        - ![ID3](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/screenshot/5_ID3.PNG)
    - ID3 bias: inductive bias
        - ![ID3Bias](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/screenshot/6_ID3Bias.PNG)

- Other consideration:
    - Decision tree continuous attributes
    - ![continousattribute](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/screenshot/7_continousattribute.PNG)
    - When to stop? 
    - ![stop](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/screenshot/8_otherconsideration.PNG)

