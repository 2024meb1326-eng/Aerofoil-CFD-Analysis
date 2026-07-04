# Aerofoil-CFD-Analysis

# Computational Fluid Dynamics with ANSYS Fluent
In this project, we used the Spalart-Allmaras RANS-based turbulence model to simulate flow over NACA 0012 and NACA 4412 airfoils. The simulations were run at varying angles of attack covering the entire lift curve for these airfoils including stall and stall recovery. The CFD simulations were made using ANSYS Fluent and compared to thin airfoil theory, vortex panel method, and NACA experimental data using MATLAB.

-------------



Simulation Automation
-------------
While the Spalart-Allmaras model is a relatively computationally inexpensive model to use, each simulation for these airfoils could take up to two hours to converge around stall. Since over 40 simulations were ran for each airfoil, it was necessary to automate this process. I did this by generating massive journal files with MATLAB that run through consecutive simulations and save all necessary data, reports, and plots.

-------------
