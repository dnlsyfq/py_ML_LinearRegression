
## Linear Regression
Lines to fit data . 
Line is a rough approximation
but it allows us the ability to explain and predict variables that have a linear relationship with each other.

<center><img src="https://render.githubusercontent.com/render/math?math=y=mx%2bc"></center>

**or**

<center><img src="https://render.githubusercontent.com/render/math?math=\hat{y}=b_1x%2bb_0"></center>

* m : The slope is a measure of how steep the line is, while the intercept is a measure of where the line hits the y-axis.
* b : The intercept is a measure of where the line hits the y-axis.
* The goal is to get the “best” m and b for our data.


### Loss 
When assign a slope and intercept to fit a set of points, we have to define what the best fit is.
For each data point, we calculate loss, a number that measures how bad the model’s (in this case, the line’s) prediction was.

loss as the squared distance from the point to the line. We do the squared distance (instead of just the distance) so that points above and below the line both contribute to total loss in the same way

<img src="img/points.svg">

squared_distanceA = 9
squared_distanceB = 1
total_squared_distance = 10

Total loss is 10 , if found a line that had less loss than 10, that line would be a better model

---

$$x_{1,2} = \frac{-b \pm \sqrt{b^2-4ac}}{2b}.$$

<center><img src="https://render.githubusercontent.com/render/math?math=y=mx%2bc"></center>

<center><img src="https://render.githubusercontent.com/render/math?math=x_{1,2} = \frac{-b \pm \sqrt{b^2-4ac}}{2b}"></center>


### Rough Code 



### Scikit Learn
