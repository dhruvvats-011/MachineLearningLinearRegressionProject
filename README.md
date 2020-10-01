# MachineLearningProject
## Linear regression
* Using linear regression and predicting model in python with data.

### Background information:
1. Aim of lInear regression: Using a set of data and condensing to a line which will output an equation

2.  Calculating r^2 = represents the proportion of variable for a dependent variable by independent values of r^2 indicates a good correlation

### Importing packages:
1. panda - read data in a csv file
2. numpy - math and regression
3. matplotlib - visualize graphs
4. seaborn - visualize graphs


### More about the main parts of the project
1. Data about a website that shows customers' 'Email', 'Address', 'Avatar', 'Avg. Session Length', 'Time on App','Time on Website', 'Length of Membership', 'Yearly Amount Spent'

2. After reading columns, it is important to understand what are the independent and dependent variables. Some information was not needed.

3. sns.pairplot(customers) shows the visualization of the numerical data

4. After the split of the training and testing data set,
LinearRegression(copy_X=True, fit_intercept=True, n_jobs=None, normalize=False)
The coefficients let us know the importance of the independent and dependent variable.

5.  Using it to test against prediction values and the real values.
tests against prediction values and the real values
mean absolute error
mean square error
root means squared error - values predicted and values observed
### Modules installing process
1.If you get any problem in installing packages from terminal you can download modules from python unofficial binaries and install them with the help of pip.
