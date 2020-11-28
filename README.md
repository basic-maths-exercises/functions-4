# Numpy functions

Based on the last three exercises you should know how to write and use Python functions when writing your programs.  Furthermore, the last two exercises have emphasised the importance of:

1. Not using global variables.  You should ensure that everything that is required to compute your function is explicitly passed to the function from the calling code.
2. Returning everything from the function that is required by the calling code.

Following this advice is important as if it is followed people can use your functions with only an understanding of:

1. What variables they need to pass to the function.
2. What the function does
3. The quantities that the function returns.

So, for example, if you follow this advice in writing a function to evaluate the sine of an angle then users of your function would only need to know that they need to pass an angle in radians to it and that the function will compute and return the sine of that angle.  They do not need to know details about how the sine of the angle is computed by the function.

In these next few exercises, you are going to learn some very good news: many of the functions you will need have already been written for you by others.  For example, if you want to compute the sine of an angle (in radians) you can do so as follows:

````
sinpi = np.sin( np.pi/6 )
````

Furthermore, Python even has variables that hold the values of some important constants that are ready for you to use (![](https://render.githubusercontent.com/render/math?math=\pi) in the example above for instance).  The above command will thus set `sinpi=0.5` as it should.

With all of that in mind, to complete this exercise you will need to write a program to plot the sine, the cosine and the tangent of x as a function of x for x in the range from ![](https://render.githubusercontent.com/render/math?math=-\pi) to ![](https://render.githubusercontent.com/render/math?math=%2B\pi).   You should use a continuous line to draw the curves and 1000 grid points.  The first of these gridpoints should be at ![](https://render.githubusercontent.com/render/math?math=-\pi) and the last of them should be at ![](https://render.githubusercontent.com/render/math?math=%2B\pi). 
