# CS224n: Natural Language Processing with Deep Learning
## Prerequisites
### **Proficiency in Python**
All class assignments are in Python (using NumPy and PyTorch). If you need to remind yourself of Python, or you're not very familiar with NumPy, you can consult online resources. If you have a lot of programming experience but in a different language (e.g. C/C++/Matlab/Java/Javascript), you will probably be fine.

### **College Calculus, Linear Algebra (e.g. MATH 51, CME 100)**
You should be comfortable taking (multivariable) derivatives and understanding matrix/vector notation and operations.

### **Basic Probability and Statistics (e.g. CS 109 or equivalent)**
You should know the basics of probabilities, gaussian distributions, mean, standard deviation, etc.

### **Foundations of Machine Learning (e.g. CS221, CS229, CS230, or CS124)**
We are formulating cost functions, taking derivatives and performing optimization with gradient descent. If you already have basic machine learning and/or deep learning knowledge, the course will be easier; however it is possible to take CS224n without it. There are many introductions to ML, in webpage, book, and video form. One approachable introduction is Hal Daumé’s in-progress A Course in Machine Learning. Reading the first 5 chapters of that book would be good background. Knowing the first 7 chapters would be even better!



# Welcome to CS224N!

In this part you will implement the word2vec model and train your own word vectors with stochastic gradient descent (SGD). Before you begin, first run the following commands within the assignment directory in order to create the appropriate conda virtual environment. This guarantees that you have all the necessary packages to complete the assignment. Windows users may wish to install the Linux Windows Subsystem9. Also note that you probably want to finish the previous math section before writing the code since you will be asked to implement the math functions in Python. You’ll probably want to implement and test each part of this section in order, since the questions are cumulative.

    
    conda env create -f env.yml    
    conda activate a2
    
## Once you are done with the assignment you can deactivate this environment by running:
    
    conda deactivate

For each of the methods you need to implement, we included approximately how many lines of code our solution has in the code comments. These numbers are included to guide you. You don’t have to stick to
them, you can write shorter or longer code as you wish. If you think your implementation is significantly longer than ours, it is a signal that there are some _numpy_ methods you could utilize to make your code both shorter and faster. _for_ loops in Python take a long time to complete when used over large arrays, so we expect you to utilize numpy methods. We will be checking the efficiency of your code. You will be able to see the results of the autograder when you submit your code to _Gradescope_, we recommend submitting early and often.
**Note:** If you are using Windows and have trouble running the .sh scripts used in this part, we recommend trying Gow or manually running commands in the scripts.
