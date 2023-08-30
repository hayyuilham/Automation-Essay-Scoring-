# Automation-Essay-Scoring
Objective of this project is to develop a system to handle the challenge in grading posed by the variety of answers in the essay questions and the high number of students. We utilized the Naive Bayes method for training a dataset and making prediction scores from students' answers by learning based on students’ essay features and tutor scores.


### Motivation:
Evaluation of online assignments and quizzes at university takes a lot of graders’s time and energy. The problem is that essay writing activities take time, concern for producing results and/or direct feedback from teachers to students, and teachers tend to be subjective in assessing essay Activities.

The challenge in grading is the variety of answers in the essay questions and the high number of students. In addition, transparency of the value result is needed immediately as a student evaluation material. To solve the problems, we could use scoring automation. One of the automated essay scoring models is by using Natural Language Processing which involves recognizing each word in student essay responses.



### Objective:
In a research collaboration with the University of Indonesia and the Terbuka University. Terbuka University is the university that has the largest e-learning system in Indonesia, The data used in this study was collected. On the other hand, the problem with using an automated essay scoring system is that there are many variations in answer file formats. Therefore, a more sophisticated extraction of the answer files is required to distinguish between the questions and answers texts. This research tries to solve the problems that have been described previously. We propose an Automation Essay Scoring (AES) system using the Naive Bayes method. The model was developed using graded assignment answers data.



### Data:
The dataset is taken from students’ assignments in Universitas Terbuka for two semesters in 2021. Each semester consists of 9 courses such as Indonesian, Citizens, Religion, English, English 1, Fundamental of Science, Social and Culture, Nationalism Ideology, and Learning on Digital Era. Each course consists of 3 modules. Scores given by tutors for each student are also available. The scores are integer numbers between 0 and 100.  The collected data consists of more than 200 answers to assignments and quizzes completed by students from one course. It has different file extensions such as PDF, docx, and html. Therefore, it must be converted into a string data type before analyzing it even further. 



### System Design:
