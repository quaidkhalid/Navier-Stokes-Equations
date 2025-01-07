# Fluid Dynamics Simulations in Python

This notebook explores various aspects of fluid dynamics through numerical simulations using Python. It covers fundamental concepts like the Navier-Stokes equations, incompressible flow, and vorticity calculations.

## Software Environment
*   **Language:** Python
*   **Libraries:**
    *   NumPy
    *   Matplotlib

You can install the libraries with the following command:
    --bash pip install numpy matplotlib

## How to Use

1.  Open this notebook in Google Colab or any other Jupyter Notebook environment.
2.  Run each cell sequentially to perform the simulations and visualize the results.

## Code Description

### Simplified Navier-Stokes Simulation

This section provides a simulation of fluid flow using a simplified 2D Navier-Stokes solver. It visualizes the velocity fields over time. The simulation begins with a circular flow driven by an initial velocity field and proceeds to update this field using a Laplacian operator. The resulting fluid flow is visualized using `matplotlib.pyplot.quiver`, with colors indicating the magnitude of the velocity.

### Incompressible Navier-Stokes Simulation

This part numerically solves the incompressible Navier-Stokes equations. It calculates and updates the velocity fields with consideration to spatial derivatives and Laplacians, providing a visualization of the resulting flow using a streamplot. This simulation showcases the development of an incompressible flow field over a series of time steps, illustrating the motion of fluid particles in a given space.

### Vorticity and Circulation

In this section, the code computes and visualizes vorticity and circulation from a given velocity field. This part defines functions to calculate vorticity, and circulation, and visualizes these using streamplots and a heatmap. This helps to analyze and understand the rotational aspects of the fluid flow.

## Additional Notes

*   The simulations are simplified for demonstration purposes.
*   The Navier-Stokes simulations are a numerical approximation of the equations.
*   The visualization is used to give a good understanding of the results.