# Bayesian Learning
## Intro to Bayesian Learning
- We are trying to do: 
    - Learn the **best** hypothesis given data and some doamain knowledge
    - Learn the **most probably** hypothesis given data with domain knowledge
    - **argmaxPr(h|D)**: 
        - **Pr(h|D)**:The probability of some particular hypothesis h, drawing from some hypothesis class. Given some amount of data (represent by "D")
        - **argmax**:We are tyring to find the best (the most likely), hypothesis h
## Bayes Rule
- Equation:
![01]()
    - **Pr(D)**: your prior belief of seeing some particular set of data.
    - **Pr(D|h)**: probability of data given the hypothesis. **Easy to figure out**
        - Example: D = {(xi, di)}. Our data is made of these training examples (supervised learning as an exmaple, di would be the labels). **Pr(D|h)** means what's the likelyhood that given that I've got all of these Xis and given that I am living in a world where this hypothesis h is true, that I would see these particular labels.
    - **Pr(h)**: Your prior on the hypothsis. **Our domain knowledge**
- Under what cercumstances, the Pr(h|D) ↑:
    - Pr(D) ↑: if you have a hypothesis has higher prior (is more likely to be a good one before you see the data)
    - Pr(D|h) ↑: similar to accuracy. if you pick a hypothesis that does a better job of labeling the data, then also your probablity of the hypothesis will go up. 
    - Pr(h) goes down, but it's not connected to the hypothesis directly
- Quiz
![02]()