# Ant Colony Optimization (ACO) for the Traveling Salesman Problem (TSP)


## Overview

This Jupyter Notebook contains Python code for solving the Traveling Salesman Problem (TSP) using the Ant Colony Optimization (ACO) algorithm. The code includes implementations of three ACO variants: Basic ACO, Max-Min Ant System (MMAS), and Elitist ACO. You can use this code to find optimal or near-optimal solutions for TSP instances.

## Requirements
Before running the code, ensure that you have the following requirements installed:

-Python 3.x

-Jupyter Notebook (if you are not already using it)

Additionally, you will need an XML file containing the distance information between cities. The code assumes that this file is named 'brazil.xml' and 'burma.xml', but you can replace it with your own file. Make sure that the XML file follows the format specified in the code.

## Installation
### Python 3.x
If you don't already have Python 3.x installed, you can download it from the official Python website: https://www.python.org/downloads/

### Jupyter Notebook
Jupyter Notebook is a popular interactive environment for running Python code. You can install it using the following steps:

1.Open a command prompt or terminal.

2.Run the following command to install Jupyter Notebook using pip, Python's package manager:

```python
pip install notebook
```
After the installation is complete, you can start Jupyter Notebook by running the following command:

```python
jupyter notebook
```
This will open a web browser window with the Jupyter Notebook interface.

## Required Libraries
To install the required libraries for this code, you can use pip. Run the following command to install the libraries:
```python
pip install numpy matplotlib lxml
```

## Usage
Open this Jupyter Notebook in your Jupyter Notebook environment.

Ensure that the 'brazil.xml' file with city distance information is in the same directory as this notebook. If you have a different XML file or want to use a different file path, modify the following line in the code to point to your file:
```python
tree = ET.parse('brazil.xml')  # Replace with the actual file path
```
Run the code cells sequentially to perform the tasks described in the notebook.

Review the generated plots to compare the performance of the three ACO variants under different parameter settings.

## Customization
You can customize the code by adjusting the parameters in the notebook as described in the notebook itself.

## Output
The code generates plots that visualize the performance of the ACO variants with different parameter settings. You can analyze these plots to determine which combination of parameters works best for your specific TSP problem instance.
