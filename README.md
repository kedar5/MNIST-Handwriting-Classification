# MNIST-Handwriting-Classification
Multi-classification problem involving classification of 28x28 bit images of handwritten numerals into distinct classes from 0-9. 



1. What was the difference in final evaluation for each algorithm on this problem?
- A difference was observed in the accuracy values for each algorithm. The Logistic regression algorithm had a higher accuracy of 92.55%. Whereas, the Naive Bayesian algorithm had a lower accuracy of 83.6%. There was a difference of 11% in the accuracy.


2. If you observed a difference in evaluation, why do you believe one algorithm performed better than the other?
- Both Naive Bayes and Logistic regression are linear classifiers.  I believe the Logistic regression algorithm performed better than the Naive Bayesian algorithm.
One of the fundamental concepts of Naive Bayes assumes that the features are conditionally independent. However, with the MNIST data set, the features represented by pixels are not conditionally independent. The stroke and neighboring pixel values are  important in determining the number written. Thus the Logistic regression algorithm is more suitable for this problem.




3. Based on the confusion matrix, which numerals contributed most to the error, and why?
- Based on the confusion matrix for Logistic Regression and Naive Bayesian algorithm, the number 5 resulted in the least accurate response, or resulted in the most error. Since it had the least instances of True positives.
