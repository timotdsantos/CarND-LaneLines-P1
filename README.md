## Road Lane Lines Detection Project

<img src="laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

Overview
---

This project is about detecting lane lines in images and videos using Python and OpenCV. The solution employs various image processing techniques. 

Two main files are submitted here: a file containing project code and a file containing a brief write up explaining the solution. 
- [Final_LaneLine_Detection.ipynb (code)](https://github.com/timotdsantos/CarND-LaneLines-P1/blob/master/Final_LaneLine_Detection.ipynb)
- [LaneLines_Detection.md (write up)](https://github.com/timotdsantos/CarND-LaneLines-P1/blob/master/LaneLines_Detection.md)

Another optional file is included (Final_LaneLine_Detection.html) which is the code notebook in html format for ease of viewing.


The specifications are further explained in [project rubric](https://review.udacity.com/#!/rubrics/322/view)


Project Write Up
---
[LaneLines_Detection.md (write up)](https://github.com/timotdsantos/CarND-LaneLines-P1/blob/master/LaneLines_Detection.md)

Contains the description and the reflection on the exercise to:
1. Describe the pipeline 2. Identify any shortcomings 3. Suggest possible improvements

The Project Code
---
[Final_LaneLine_Detection.ipynb (code)](https://github.com/timotdsantos/CarND-LaneLines-P1/blob/master/Final_LaneLine_Detection.ipynb) 
[(Final_LaneLine_Detection.html)](https://github.com/timotdsantos/CarND-LaneLines-P1/blob/master/Final_LaneLine_Detection.html)

Contains all project code. File dependencies are included in the repository.

Below are steps to resolve dependencies and run the project. (Taken from original CarND Project 1 Readme)

**If you have already installed the [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) you should be good to go!   If not, you can install the starter kit or follow the install instructions below to get started on this project. **

**Step 1:** Getting setup with Python

To do this project, you will need Python 3 along with the numpy, matplotlib, and OpenCV libraries, as well as Jupyter Notebook installed. 

We recommend downloading and installing the Anaconda Python 3 distribution from Continuum Analytics because it comes prepackaged with many of the Python dependencies you will need for this and future projects, makes it easy to install OpenCV, and includes Jupyter Notebook.  Beyond that, it is one of the most common Python distributions used in data analytics and machine learning, so a great choice if you're getting started in the field.

Choose the appropriate Python 3 Anaconda install package for your operating system <A HREF="https://www.continuum.io/downloads" target="_blank">here</A>.   Download and install the package.

If you already have Anaconda for Python 2 installed, you can create a separate environment for Python 3 and all the appropriate dependencies with the following command:

`>  conda create --name=yourNewEnvironment python=3 anaconda`

`>  source activate yourNewEnvironment`

**Step 2:** Installing OpenCV

Once you have Anaconda installed, first double check you are in your Python 3 environment:

`>python`    
`Python 3.5.2 |Anaconda 4.1.1 (x86_64)| (default, Jul  2 2016, 17:52:12)`  
`[GCC 4.2.1 Compatible Apple LLVM 4.2 (clang-425.0.28)] on darwin`  
`Type "help", "copyright", "credits" or "license" for more information.`  
`>>>`   
(Ctrl-d to exit Python)

run the following commands at the terminal prompt to get OpenCV:

`> pip install pillow`  
`> conda install -c menpo opencv3=3.1.0`

then to test if OpenCV is installed correctly:

`> python`  
`>>> import cv2`  
`>>>`  (i.e. did not get an ImportError)

(Ctrl-d to exit Python)

**Step 3:** Installing moviepy  

We recommend the "moviepy" package for processing video in this project (though you're welcome to use other packages if you prefer).  

To install moviepy run:

`>pip install moviepy`  

and check that the install worked:

`>python`  
`>>>import moviepy`  
`>>>`  (i.e. did not get an ImportError)

(Ctrl-d to exit Python)

**Step 4:** Opening the code in a Jupyter Notebook

You will complete this project in a Jupyter notebook.  If you are unfamiliar with Jupyter Notebooks, check out <A HREF="https://www.packtpub.com/books/content/basics-jupyter-notebook-and-python" target="_blank">Cyrille Rossant's Basics of Jupyter Notebook and Python</A> to get started.

Jupyter is an ipython notebook where you can run blocks of code and see results interactively.  All the code for this project is contained in a Jupyter notebook. To start Jupyter in your browser, run the following command at the terminal prompt (be sure you're in your Python 3 environment!):

`> jupyter notebook`

A browser window will appear showing the contents of the current directory.  Click on the file called "P1.ipynb".  Another browser window will appear displaying the notebook.  Follow the instructions in the notebook to complete the project.  

**Step 5:** Complete the project and submit both the Ipython notebook and the project writeup

