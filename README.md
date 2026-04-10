# Introduction

These Jupyter notebooks provide an introduction to Python for students taking the course **Advanced Robotics Laboratory (00340401)**.

Each notebook includes short exercises to help you practice what you have learned. For every exercise notebook, there is also a solved version. For example:

* `1-Introduction-to-Python-student.ipynb`
* `1-Introduction-to-Python.ipynb` (solved)

Throughout the notebooks, we will work with an imaginary [Crazyflie](https://www.bitcraze.io/products/crazyflie-2-1/) drone. Crazyflie drones are widely used in research, making them a useful example for applying Python concepts. By the end of the notebooks, you will have built a simple trajectory simulation for a Crazyflie drone.

> **Note:** This program is only a simplified example and does not represent a realistic drone simulation.

The notebooks cover the following topics, which are directly related to the other labs:

1. Introduction to Python: basic syntax
2. Matrices and vectors
3. Basic plotting
4. The `class` keyword

Feel free to skip any notebook that seems too easy. If you already have experience programming in Python, such as from a previous Python course, you can likely skip the introductory notebook.

> **Warning:** We recommend that you **do not** use LLMs to solve the exercises. They are optional, and you will learn more by working through them on your own.

# Installation

## Google Colab (recommended)

The easiest way to run these notebooks is with [Google Colab](https://colab.research.google.com/). No installation is required.

1. Open Google Colab.
2. Click **File** → **Open notebook** → **GitHub**.
3. Enter the repository URL.
4. Select the notebook you want to run.
5. Click the play button to execute the cells.

You can also upload a notebook directly to Colab by dragging and dropping the `.ipynb` file.

## Running locally

To run the notebooks locally, you will need to:

1. Install Python
2. Install `miniconda`
3. Install the required dependencies

Instructions for Windows, macOS, and Linux are provided below.

### Windows

* Go to the [Python downloads](https://www.python.org/downloads/windows/) page.
* Download the correct version for your system, usually **x86-64**.
* Follow the installer steps, and make sure to add Python to your `PATH` ([Why?](https://realpython.com/add-python-to-path/)).
* Install `miniconda` by following the instructions [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

### macOS/Linux

Python is often already installed by default. We recommend installing `miniconda` so that you can avoid installing packages into your system Python environment and easily work with Jupyter notebooks.

To run these notebooks locally, install [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

After installing `conda`, create the environment using the following command after downloading `robotics-lab-intro-environment.yml`:

```bash
conda env create -f robotics-lab-intro-environment.yml
```

If you are working locally, we also recommend installing [Visual Studio Code](https://code.visualstudio.com/).

Once the environment has been created, you will be able to run the notebooks using the `robotics-lab-intro` environment.

## Dependencies

If you prefer to install the dependencies manually, you will need these two packages:

1. `numpy`
2. `matplotlib`



## PDF Version
The PDF version includes the latest solved versions alonside the instructions included in the `README.md`