I included all the tasks of the midterm that have to be done on R. I used google colab.
Rmd folder contain all the rmd files of all the tasks (4).
Where as Ipynb folder contains the ipynb file whuch can be opened on jupyter or colab.
where as rmd executable contains the executable chrome files of rmd. which will diplay the output of rmd file
 The four tasks are:
 Task 1:
 Use the mtcars dataset in r demonstrate how to filter rows where the mpg is greater than  and arrange the results in descending order of hp using the dplyr:
 
 The library used in task 1 is dplyr.
 dplyr which is used for data manipulation, providing a consistent set of verbs that help you solve the most common data manipulation challenges: mutate() adds new variables that are functions of existing variables. select() picks variables based on their names.
 
 Task 2:
 data visualization witth ggplot 2 create a scatter plot using ggplot2 library to show the relation between wt and mpg in the mtcars dataset. customize the plot to include a title, axis labels and a regression line
 we will use ggplot2.
 library ggplot2 which is used for or creating data visualizations based on the "Grammar of Graphics." It's used to create plots by providing data, defining aesthetics (how data maps to visual elements), specifying graphical primitives, and adding layers
 
 Task 3:
 statical analysis in R write r code to perform one sample t test on a given numeric vector to check if its means is significantly defferent from 10. provide an example with simple dataset
  
  In this we have to find t test
  T-tests are used to test hypotheses about the differences between means. They help determine if the observed difference between two group means is likely due to a real effect or simply due to random chance. 
One-sample t-test: Compares the mean of a single sample to a known or hypothesized value. 
  Task 4:
  machine learning with caret use the caret package to train a linear regression model predicting mpg from other variables in mtcars dataset. Write code to preprocess the data (e.g. scaling ), split it into training and testing sets, train the model and evaluate its performance using metrics like RMSE 
  in this we will use caret library.
  One of the most powerful and popular packages is the caret library, which follows a consistent syntax for data preparation, model building, and model evaluation, making it easy for data science practitioners. Caret stands for classification and regression training and is arguably the biggest project in R
