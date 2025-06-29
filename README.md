# CFD

This project implements a 2D Computational Fluid Dynamics (CFD) solver using the Finite Volume Method (FVM) to simulate steady-state, incompressible, laminar flow over a NACA 0012 airfoil. The solver is written in Python and solves the Navier–Stokes equations on a structured O-grid mesh, with wake refinement.

⚠️ Note: The current version of the code does not converge, likely due to poor mesh quality (e.g. high skewness near the trailing edge). However, the implementation of the numerical methods and the solver logic are believed to be correct.
