# vortices-sphere
Create a velocity field file with vortices on a sphere for magnetohydrodynamics 
or hydrodynamics code. Velocity field derived from the steady state solution in 
"Stuart vortices on a sphere" by Dr. Darren Crowdy.

INPUTS: File for mesh grid from MHD or HD code. N=number of vortices, a=parameter 
        for vortex strength, theta_0=polar position of vortices on the sphere. 
        
OUTPUTS: File for components of velocity in spherical coordinates at each midpoint 
         on the grid. A plot of the velocity field on the grid is shown at the end 
         of each notebook.
