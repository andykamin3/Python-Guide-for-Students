# Introduction
This set of Jupyter notebooks serve as an introduction to Python for students taking the course Advanced Robotics Laboratory (00340401). 

All of the notebooks will include little exercises to practice what you've learned and will include a solved version like `1-Introduction-to-Python-student.ipynb` and `1-Introduction-to-Python.ipnyb` (solved). 

Throughout this notebooks we will work with an imaginary [Crazyflie](https://www.bitcraze.io/products/crazyflie-2-1/) drone. These drones are very common as a research tool and will give us a great example on which to apply our Python knowledge. By the end of these notebooks you will have built a very simple, crazyfile trajectory simulation. 

> **Note:** The resulting program does not represent how a real drone simulation works and it is just a toy example. 

We will discuss the following subjects which are directly related to the other labs:

1. Introduction to Python: Basic syntax 
2. Matrices and vectors
3. Basic plotting 
4. The `class` keyword

Feel free to skip any notebook that feels too easy for you. If you have ever programmed anything using Python (like in the Python course) you can probably skip the intro notebook.


> **Warning:** We recommend you **do not** use LLMs when solving these exerices. They are not mandatory and you will learn more by solving them yourself. 


# Installation
## Google Colab (Recommended)

The easiest way to run these notebooks is using [Google Colab](https://colab.research.google.com/). No installation required:

1. Open Google Colab
2. Click **File** → **Open notebook** → **GitHub**
3. Enter the repository URL
4. Select the notebook you want to run
5. Click the play button to execute cells

Alternatively, you can upload a notebook directly to Colab by dragging and dropping the `.ipynb` file.
## Locally
To run this set of notebooks you will need a local installation of 
[Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html). 
After installing `conda` you can begin by creating the environment using the command:
```bash
conda env create -f robotics-lab-intro-environment.yml
```
If working locally we suggest downloading 
[Visual Studio Code](https://code.visualstudio.com/)


