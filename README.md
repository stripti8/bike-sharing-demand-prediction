# bike-sharing-demand-prediction
<h1 align="center"> Bike-sharing-demand-prediction </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

![Screenshot (219)](https://user-images.githubusercontent.com/85070726/161031482-d62503d2-3243-4a9c-9b8c-516f383a947d.png)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
 
## Objectives
The aim of the project is to predict the bike count required at each hour for stable supply. It is important to make the rental bike available and accesible to public at right time and reduce waiting time for their mobility comfort.


## Project Desciption
**capstone_project.ipynb** - Include all function required to predict the bike sharing demand

**Technical_documentation.docx** - Include the documentation for the project.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
 
## Linear Regression
linear regression model assumes that the relationship between the dependent variable and independent is linear. This relationship is modeled through a disturbance term or error variable ε — an unobserved random variable that adds "noise" to the linear relationship between the dependent variable. Thus the model takes the form
Regression is done on numerical data which is continuous.
Linear regression consist of dependent and independent variables related linear to each other
our basic aim is to create best fit line from the dependent and independent variable between two axis, it is expressed in straight line

![Screenshot (227)](https://user-images.githubusercontent.com/85070726/161062232-c2a2a1cc-3dd6-4aac-988f-f0ff85c588ad.png)


**Y=B0+B1X1+B2X2+……..+e**

**B0** is intercept 
**b1, b2...** are the parameters
**Y** is actual value
**x1,x2** are independent variables 
**e** is noise

Best fit line in which error between predicted and actual value is minimum. Residual error = (predicted-actual value)2

Our goal is to locate optimum model complexity, if complexity of model exceeded then overfiting of model occur while complexity falls the underfiting will occur in that case we use regularization L1 and L2 it is used to regularize the size of co efficient.

### Lasso regression (L1 Regularization)
It is a type of linear regression that used for shrinkage and to avoid overfitting in the data. To make the optimal solution we use penalty term in cost function and minimize the cost function from value is lambda * mag(Bij) and make final value become zero.

### Ridge Regression (L2 Regularization)
This method performs L2 regularization. When the issue of least-squares are unbiased, and variances are large, this results in predicted values being far away from the actual values. to make the optimal solution we use penalty term in cost function and minimize the cost function from the value is lambda * (Bij)2 and make final value close to zero and shrink the value.
 
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

 Tripti Singh  | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast
 
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tripti-sikarwar-2172a1266/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/stripti8)

 
 
