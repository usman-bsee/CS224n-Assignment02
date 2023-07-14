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

We'll be using Python throughout the course. If you've got a good Python setup already, great! But make sure that it is at least Python version 3.5. If not, the easiest thing to do is to make sure you have at least 3GB free on your computer and then to head over to (https://www.anaconda.com/download/) and install the Python 3 version of Anaconda. It will work on any operating system.

After you have installed conda, close any open terminals you might have. Then open a new terminal and run the following command:

## 1. Create an environment with dependencies specified in env.yml:
    
    conda env create -f env.yml

## 2. Activate the new environment:
    
    conda activate cs224n
    
## 3. Inside the new environment, install IPython kernel so we can use this environment in jupyter notebook: 
    
    python -m ipykernel install --user --name cs224n


## 4. Homework 1 (only) is a Jupyter Notebook. With the above done you should be able to get underway by typing:

    jupyter notebook CS224n_Assignment01.ipynb
    
### 5. To make sure we are using the right environment, go to the toolbar of exploring_word_vectors.ipynb, click on Kernel -> Change kernel, you should see and select cs224n in the drop-down menu.

## To deactivate an active environment, use
    
    conda deactivate
