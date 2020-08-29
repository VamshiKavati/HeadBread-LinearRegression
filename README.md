# HeadBread-LinearRegression
Head Brain example - Linear regression 

# This is a basic example to understand Linear Regression

step - 1 :

-> Import all the required libraries 

-> Read the required files into x and y

step - 2

-> Now to calculate the Coefficients use the formula 

              Σ(x - mean_x)(y - mean_y)
    b1 or m = --------------------------
                    Σ(x - mean_x)
                    
-> Now you have the "m" value 
-> to fing c value, substitute the m in the below formula

          y = mx + c
step - 3

-> now find the Y value which is to be plotted to get regression line

-> we have m and c values and with the help of x predict the y_pred values:

                 y = m * x + c
                 
-> Plot the regression line with scatter points 

# To know the goodness of fit ( how god the model is performing)

-> You can use R2(R - square) m or scikit learn (ml model)

-> for finding R2 the formula is :

                    Σ (pred_y - y)         predicted value of y  - y
              r2 = -----------------
                    Σ (mean_y - y)         mean of y - y
                    
