# Project3-OpenClassrooms
Build an app for public health

## Business case
This project consists int the proposal and feasibility study of an application for health based on the Open Food Facts dataset.

My application idea is the following: the user will use the application to scan a product, and the application will propose similar products, i.e. in the same category, with similar macronutrient values, with the same Nutri-score or a higher Nutri-score, but with fewer calories eating.

## Main results
From the initial dataset, potentially interesting variables for the application were selected: macronutrients, vitamins, nutrients that enter into the Nutri-score calculation, variables linked to the product category and variables linked to the Nutri-score. A first analysis of these variables made it possible to remove outliers and missing values were replaced.

After data cleaning several analyses were carried out:

-	univariate analyses, to study the distributions of variables
-	bivariate analyses to study the relationship between nutritional score and nutritional information; the relationship is the one expected: increasing trend for the elements that contribute negatively to the score and decreasing for the positive elements
-	a PCA which showed that the variables are weakly correlated

The function that simulates the application by choosing a random product and finding similar products with fewer calories has given good results.

The dataset is thus reliable, it is possible to use it to develop the prototype of the application.

## Aquired skills

-	Perform multivariate statistical analysis
-	Communicate your results using readable and relevant graphic representations
-	Perform univariate statistical analysis
-	Perform cleansing operations on structured data

