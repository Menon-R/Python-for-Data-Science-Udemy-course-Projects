# DESCRIPTION

**Test the Law of Large Numbers for N random normally distributed numbers with the mean=0 and standard deviation (stdev)=1.
Using a python script, count how mant of these generated numbers fall between the intervals of -1 and 1 and divide the total quantity of N.
Data Known: Expected value of x (E(x))= 68.2%
Check Mean(Xn)~ E(x) as the script runs with increasing N values**

# SOLUTION

Using numpy package in python to generate random numbers from the randn fucntion in the numpy package, we can write a for loop for iteration purpose and add in the hit-ratio for counting the probability percentage.
As the value of the sample size (N) increases it approaches closer to the Expected value, which in this case is 68.2%.

The code is provided in the .ipynb file in this section and an image of Bell Curve is provied to visualize a Normal Distribution.
