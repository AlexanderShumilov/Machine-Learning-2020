# Machine-Learning-2020

## HW1:

PRACTICE 1|2|3|4.1|4.2|5.1|5.2|6|7
Scores (0/1) 1|1|1|1|1|1|1|1|1|
Final Practice score (weighted sum) = 12
COMMENTS
nan
THEORY 1|2|3|4|5|6.1|6.2|7|8.1|8.2|9|10
Scores (0/1) 0|0|1|1|1|1|1|1|1|1|1|nan|
Final Theory score (sum) = 9
COMMENTS
(1) A should be independent of w (2) Where is b?
FINAL SCORE = 21/22(24)

## HW2:
14/14(15)
Practice:
Task 1: in case you are curious about why your results are slightly different than the ones from sklearn: sklearn normalizes the weights a little differently than in lectures' slides - at first you calculate all of the weights and only then normalize. Both variants are correct though! 
Theory:
Task 5: a lot of unfortunate misprints: f_1 = h_0 + f_0, so in cell 13,  instead of assigning [-7.4, -7.4, 4.93, 4.93, 4.93] to f_1, you should assign it to  h_0,  because of that a mistake occurred - h_1 is calculated incorrectly, it should be  h_1 = [-1.42, -1.42, -1.42, -1.42,  5.67]; the splits are wrong, instead of 53 (which is not even in the given dataset) there should be 63.

## HW3:
25/27(30)

## HW4:
17/18
Regarding task 2, for example you have,
\mathbb{E}(b + aY_0) = b + a\mathbb{E}(Y_0) = b. You do not distribute the expectation on b.  And similar details happen throughout the exercise although it is explicitly asked to list each step.
