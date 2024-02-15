# Regression-Based-on-Duckworth-Lewis-Method

The file contains data on ODI matches from 1999 to 2011. It is taken from this site. There is an R code for finding the 'run production functions' in this site, but you will do something marginally different in the following assignment. Using the first innings data alone in the above data set, find the best fit 'run production functions' in terms of wickets-in-hand w and overs-to-go u. 
Assume the model Z(u,w) = Z0(w)[1 - exp{-Lu/Z0(w)}]. Use the sum of squared errors loss function, summed across overs, wickets, and data points.

Note that your regression forces all slopes to be equal at u = 0. You should impose the conditions that L is nonnegative and the Z0(w)'s are ordered and nonnegative. You should provide a plot of the ten functions, and report the (11) parameters associated with the (10) production functions, and the normalised squared error (total squared error summed across overs, wickets, and data points, and normalised by the number of data points) in your pdf file.
