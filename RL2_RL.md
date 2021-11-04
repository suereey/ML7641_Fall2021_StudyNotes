# Reinforcement Learning
## Intro to RL
![02](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/02.PNG)
![03](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/03.PNG)
- RL API
![04](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/04.PNG)
- 3 Approaches for RL
![05](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/05.PNG)
- This course focus on the **value-function**based RL
    ![06](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/06.PNG)
        - U(s) is defined fo reach state, the utility of being in thi sstsate
        - R(s) reward for arriving this state
        - The rest section: the discounted reward of the future. In the future, to leave this state:
            - choose some action, 
            - take the expectation over all possible next states, arriving some next state T(s, a, s') and the U(s')
        - Policy: consider all the actions we can take to leave tht state, look at their expectd values -> **Q function**

- **Q function**
![07](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/07.PNG)

![08](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/08.PNG)
- Estimating Q from transition
![09](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/09.PNG)
![11](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/11.PNG)
- Learning incrementally
![10](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/RL1_RL2/10.PNG)

- Choosing actions
![11]()

## Summary
![16]()