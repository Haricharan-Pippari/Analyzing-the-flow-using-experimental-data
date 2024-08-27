# Analyzing-the-flow-using-experimental-data

There are three codes available in the Files folder:

  1. The "**Problem1.mlx**" plots normalized autocorrelation function by keeping the time seperation in milliseconds and also calculates Integral Time Scale.
     **Note:** In "Hotwire.dat, the first and second columns are time and velocity respectively.
  
  2. In "**Problem2.mlx**", a dye visualization video of vortex (Karman) shedding downstream the cylinder is imported. Three points are considered, P1, P2, P3, which are equidistant from each in horizontal line approximately at the vortex streams below the cylinder. This code solves for normalized correlation function at point P1, P1 and P2, P1 and P3 for fluctuating time signals. By using these plots and data it finds the convection velocity of the vortices.
  
  3.  **"Problem3.mlx"** imports the PIV data and solves for instantaneous, average and rms velocities at x = 30 mm along y direction. Then in plots the correlation contour by considering a reference point at x = 30 mm and y = 0 mm. Again three points are considered, P1(x=30,y=5), P2(x=33, y=5) and P3(x=36,y=5), and normalized correlation is found for the fluctuating u velocity similar to **"Problem2"** and solves for the convection velocity of the travelling vortices.
     **Note:** In "PIVdata.txt", the data is taken at 365Hz. It contains 4 columns, the first, second, third and fourth columns include variables, x, y, U and V respectively.


**IMP:** ".mlx" is the MATLAB Live Script extension

-Haricharan P
