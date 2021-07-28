# LDA_Face_Recognition
Practical Implementation of Linear Discriminant Analysis to identify faces.

## CONTENTS OF THIS FILE

* Description
* Requirements
* Installation
* Directory Structure
* Usage
* Credits

### Description 

Linear Discriminant Analysis or Normal Discriminant Analysis or Discriminant Function Analysis is a supervised dimentionality reduction technique. In LDA our main intension is to find the transformation matrix (W), by which we can project our data such that they will be linearly separable. Transformation matrix depends upon two things, Within class scatter matrix (SW) and between class scatter matrix (SB). 

Then we will select a criterion function (J) which maximizes the between class and minimize the within class scatter. J is product of inverse of SW and SB. A major problem occurs in LDA when the sample size is less than the dimentions, known as the Small Sample Size problem (SSS). To tackle this, we will first apply PCA to reduce dimentions and then apply LDA over it.

### Requirements

1. Python 3
2. Numpy
3. Sci-kit Learn
4. Pandas
5. Matplotlib
6. Jupyter Notebook

### Installation

1. Python

Step 1: Visit and download Python from https://www.python.org/downloads/
Step 2: Install and add Python to path

2. Numpy

In command prompt
> pip install numpy

3. Sci-kit Learn

In command prompt
> pip install sklearn

4. Pandas

In command prompt
> pip install pandas

5. Matplotlib

In command prompt
> pip install matplotlib

6. Jupyter

In command prompt
>pip install jupyterlab

For conda users
>conda install -c conda-forge jupyterlab

To start Jupyter type 
>jupyter notebook

### Directory Structure
    .
    ├── src                     # Source files
    │   ├── s1
    │   │   ├── 1.pgm
    │   │   ├──  ...
    │   │   ├── 10.pgm
    │   ├── s2
    │   ├── ...
    │   ├── s40
    │   ├── lda_face_recognition.ipynb   # Jupyter Notebook 
    ├── LICENSE
    └── README.md


### Usage

Open src/lda_face_recognition.ipynb in Jupyter. After running, you will observe the performance of  LDA in identifying faces through the classification accuracy curve. Two type of distances were considered, Euclidean and Mahalanobis distance to generate the classification accuracy curve.

### Credits

Ajay Biswas

