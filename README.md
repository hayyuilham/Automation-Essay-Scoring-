# Automation Grading Essay: Data Science, Machine Learning and Artificial intelligence
project collaboration with Gadjah Mada University, Terbuka University, and University of Indonesia.


### Automation-Essay-Scoring
The objective of this project is to develop a system to handle the challenge in grading posed by the variety of answers in the essay questions and the high number of students. We make prediction scores from students' answers by learning based on students’ essay features and tutor scores.

### Motivation:
Evaluation of online assignments and quizzes at university takes a lot of graders’s time and energy. The problem is that essay writing activities take time, concern for producing results and/or direct feedback from teachers to students, and teachers tend to be subjective in assessing essay Activities.

The challenge in grading is the variety of answers in the essay questions and the high number of students. In addition, transparency of the value result is needed immediately as a student evaluation material. To solve the problems, we could use scoring automation. One of the automated essay scoring models is by using Natural Language Processing which involves recognizing each word in student essay responses.

### Work Done
* Built an automated grading essay assignment system laveraging students' answers from text and image format.
* Implemented an approach using BERT for contextual embedding layer and modeling layer with Bi-LSTM
* Implemented data augmentation to enhance model performance
* Achieved an average kappa value of 0.8387962 and reduced the Mean Absolute Error (MAE) compared to the machine learning model (Naive Bayes) by 3.33

***


### Report
You can access the training code of the model and the resulting images from the model development in the web app system, attachment above. 


### Structure and Acknowledgements 
* "AESENG.ipynb": Contains code and result evaluation approach Bert and Bi-LSTM model. 
* "Flow.JPG": Contains the workflow of the developed model. 
* "result.JPG": Contains result image from evaluations with average kappa score.
* "trial_scoring_essay.JPG": contains a sample visualization web app for grading essay answers.


### Link Web system
https://student.aesonline-ut.com/
