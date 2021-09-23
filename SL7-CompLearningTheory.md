# Computational learning theory
## Addressing 3 important problems
- Defining learning problems
- Showing specific algorithms work
- Show these problem are afundamentally hard

## Resources in machine learning
- ![01](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/01.PNG)

## Defining inductive learning (learning from examples)
- probability of successful training (1-δ)
- # of examples to train on (m)
- complexity of hypothesis class (complexity of H, too complet-> overfit)
- accuracy to which target concept is approimated (ε)
- manner in which training examples presented (batch/online)
- manner in which training examples selected

## Selecting training examples (learner/teacher)
- Learner asks questions of teachers. C(X)? Learner
- Teacher gives examplse to help learner. Teacher choose , tells C(X)
- Fixed distribution. X chosen from D by native
- Evil- worst distribution

- Teaching via 20 questions. It would be different it teacher or learener ask the question.
	- Example 1. Teacher's question is not contrained.
		- ![02](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/02.PNG)
	- Example 2. Teacher's question is not contrained.
		- Know the hypothesis
		![03](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/03.PNG)
		- Don't know the hypothesis
		![04](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/04.PNG)
	- Example 3. Learner with constrained queres. 
		- Very hard to guess.
		![05](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/05.PNG)
	- Example 4. Learner with mistake bounds.
## Definitions
- computational complexity: How much computational effort is needed for a learner to converge to the answer?
- sample complexity (batch): How many traning samples are needed for a learner to create a successful hypothesis
- mistake bounds (online): How many misclassification can a learner make over an infinite run?
![06](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/06.PNG)
- version space:
	- Definition:
	![07](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/07.PNG)
	- Example:
	![08](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/08.PNG)
## PAC learning
- Error of the hypothesis
	- training error
	- test error
	-![09](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/09.PNG)
	mathematically: Error with respect to some distribution D of some hypothesis h, is the probablity that if we draw the input X from that distribution that you're going to get a mistach between the true label (according to the concept) and the hypothesis that we are currently evaluating.
- Definition of PAC (probably approximately correct)
	![10](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/10.PNG)
- Example:
	![11](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/11.PNG)
- ε-exhasted version space. 
	- equations mean: version space that is derived from a particular sample is considered ε exhausted if and only if for all the hypotheses that are in that version space they have low error.
	- another way to say: sth is ε-exhausted exactly in the case when everthing that you might possibly choose has an error < ε.
	- Example:
	![12](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/12.PNG)
- Haussler Theorem
	- bounded the true error as a function of training examples that are drawn
	![13](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/13.PNG)
	![14](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/14.PNG)
	- Example
	![15](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/15.PNG)

## Summary
![16](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/SL7/16.PNG)