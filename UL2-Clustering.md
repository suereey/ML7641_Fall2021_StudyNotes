# Clustering
## Unsupervised learning
- Supervised learning: mapping input and output
- Unsupervised learning: data description
    ![01](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/01.PNG)
- Basic unsbupervised learning problem: **clustering**
    ![02](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/02.PNG)
## Clustering
- Single linkage clustering (SLC)
    - k is the input for this algorithm
    ![03](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/03.PNG)
    ![04](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/04.PNG)   
    ![05](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/05.PNG) 

    - runtime
    ![06](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/06.PNG) 

    - Issues with SLC
    ![07](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/07.PNG)

- k means clustering
    - pick a k (k number of clusters that we want to have)
    -
    ![08](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/08.PNG)
    - k-means is good. prove: k-means in euclidean space
    ![09](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/09.PNG)
    - k-means optimization (more like hill climbing)
    ![10](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/10.PNG)
    ![11](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/11.PNG)
    ![12](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/12.PNG)
    - preperties of k-means clustering:
        - ![13](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/13.PNG)
        - answer: a, b, and c (or d/e/f)
        - Solution: Random restart
- Soft clustering
    - Problem with K-means, example the point "d"
    ![14](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/14.PNG)
    - Solution: "d" can be shared by two groups by soft clustering
    - soft clustering
    ![15](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/15.PNG)
    - Make problem easier: break it into multiple hidden variables
    ![16](https://raw.githubusercontent.com/suereey/ML7641_Fall2021_StudyNotes/main/Screenshot/UL2/16.PNG)
    - Expected maximization (**EM**)
    ![17](https://github.com/suereey/ML7641_Fall2021_StudyNotes/blob/main/Screenshot/UL2/17.PNG)