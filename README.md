# Brachistochrone Curve Analysis
This Jupyter notebook provides an analysis of a simplified Brachistochrone problem, a classic problem in calculus of variations.
This notebook first calculates the time taken for a ball to reach position pi, then optimize pararameters a,b,c,d for the following equation
<p align="center">
y(x) = -x + a*sin(x) + b *sin(2x) + c*sin(3x) + d*sin(4x)
</p>
Such that the time it takes for a particle to slide down this curve is the shortest.

The notebook begins with a brief introduction to the problem, and then moves on to explain the mathematics behind the problem. It provides a step-by-step guide on how to derive the equations that describe the motion of the particle along the curve and eventually forms the **ODE**.

Next, to solve the ODE in the Brachistochrone problem, the notebook uses the **RK4 method** to numerically approximate the solution. It also calculates the time it takes for the particle to slide down the curve for different starting heights. The notebook then goes on to optimize the function with the **Nelder-Mead algorithm** and eventually plot the resulting brachistochrone curve.

<p align="center">
<img width="337" alt="image" src="https://user-images.githubusercontent.com/85885666/233914499-693a7efe-53ed-40b3-a3c4-cb01a3bca0e3.png">
</p>

## Requirements
To run the notebook, you will need to have Python 3 and the following libraries installed:

<ol>
  <li>numpy</li>
  <li>matplotlib</li>
</ol>
You can install these packages by running the following command using pip:
<code>pip install numpy matplotlib</code>

## Usage
To use this notebook, you can either download it directly from the repository or clone the entire repository to your local machine. Once you have the notebook, you can open it using Jupyter Notebook or JupyterLab. 

To run the notebook, you can execute each cell in sequence. The notebook includes detailed explanations of each step and how it contributes to solving the simplified Brachistochrone curve problem.

## License
The code in this repository is licensed under the MIT License. See [LICENSE.md](LICENSE.md) for more information.
