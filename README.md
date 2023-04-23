# MINI-PROJECT
Linear regression is a statistical method for modeling relationships between a dependent variable with a given set of independent variables. 
Simple linear regression is an approach for predicting a response using a single feature.
In order to provide a basic understanding of linear regression, 
we start with the most basic version of linear regression, 
i.e. Simple linear regression.

REGRESSION-PREDICTION-OF-RED WINE's QUALITY:

I'm predict RED WINE's QUALITY Dataset using Simple Linear Regression:
START:
I get dependent variable is Precipitation columns and independent variable is quality columns. 
Then unwanted coulums are deleted using DROP key. 
locate and reshape the values of X and Y. 
Then using the MatPlotLib to visible a Scatter plot of X,Y. 
split the values of x and y using train & test methods.
Thus the simple linear regression was implemented.

RESULT:

using sklearn find the mean squard error and mean absolute error.
[mean_squared_error(y_test,y_predict)=0.5388879747779874]
[mean_absolute_error(y_test,y_predict)=0.2043528492213248].

LOOKER STUDIO: I'm also predict the same data set in looker studio Using table to
fixed acidity,volatile acidity,citricacid,
residual sugar,chlorides,free sulfurdioxide,
total sulfur dioxide,density,pH	sulphates,alcohol,quality,
i find relationship between alcohol and quality and count using Bar chart and Pie chart, 
i find relationship between alcohol and quality  using pie chart, and 
i find Relationship between quality and Precipitaion using line chart
