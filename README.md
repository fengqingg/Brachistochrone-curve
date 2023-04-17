# Brachistochrone Curve Analysis
This Jupyter notebook provides an analysis of a simplified Brachistochrone problem, a classic problem in calculus of variations.
This notebook first calculates the time taken for a ball to reach position pi, then optimize pararameters a,b,c,d for the following equation $$(y(x) = -x + a*sin(x) + b *sin(2x) + c*sin(3x) + d*sin(4x))$$ such that the time it takes for a particle to slide down this curve is the shortest.

The notebook begins with a brief introduction to the problem, and then moves on to explain the mathematics behind the problem. It provides a step-by-step guide on how to derive the equations that describe the motion of the particle along the curve and eventually forms the **ODE**.

Next, to solve the ODE in the Brachistochrone problem, the notebook uses the **RK4 method** to numerically approximate the solution. It also calculates the time it takes for the particle to slide down the curve for different starting heights. The notebook then goes on to optimize the function with the **Nelder-Mead algorithm** and eventually plot the resulting brachistochrone curve.

<p align="center">
<img width="333" alt="image" src="https://user-images.githubusercontent.com/85885666/232539778-15e48482-a7c0-40be-802f-e03c51c99d51.png">
</p>

Getting Started
To run the notebook, you will need to have Python 3 installed on your computer, as well as the following libraries:

numpy
scipy
matplotlib
You can install these libraries using pip:

pip install numpy matplotlib

Once you have installed the necessary libraries, you can open the notebook in Jupyter and run the cells in order.
