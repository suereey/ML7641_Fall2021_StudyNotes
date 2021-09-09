# Regression and Classification
- Summary slides:
![summary](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/1_regressionsummary.PNG)

# Neural Networks
## Artificial Neural Network
- Keywords:
    - perceptron
    - activation 
    -fitting threshold
- Example: 
    - ![ann](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/2_ArtificialNN.PNG)
- How powerful is a perceptron unit
    - And
        - ![and](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/3_perceptron.PNG)
    - Or: move down the line for And (change θ); or many other ways as well.
    - Not:
        - ![not](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/5_perceptron.PNG)
    - XOR:
        - ![XOR](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/6_perceptron.PNG)

## Perceptron traning
- Given examples, find weights that map inputs to outputs.
    - Perceptron rule (**threshold**)
    - gradient descent/delta rule (**unthresholded**)
- Perceptron rule
    - ![prceptronrule](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/7_perceptron.PNG)
- Gradient descent
    - ![gradientdescent](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/8_perceptron.PNG)
- Compare 2 rules:
    - ![compare](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/9_perceptron.PNG)
    - It is not a continous function, can not do differential. Change to continous -> Sigmoid function
- Sigmoid function
    - [sigmoid](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/10_sigmoid.PNG)
- Neural network sketch
    - [nnsketch](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/10_nn.PNG)
- Optimize weight
    - ![weight](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/11_weight.PNG)
- Restriction bias
    - ![bias01](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/12_restrictionbias.PNG)
- Preference bias
    - ![bias02](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/13_restrictionbias.PNG)
- Summary
![summary](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL2SL3_Screenshot/14_summary.PNG)