Assignment 2
------------------------------

For this assignment, you'll be working with the county level dataset to predict home ownership rates using conditional means. You'll need to select the county-level characteristics that you think might be related to home ownership rates. Please complete the following steps (hint, use a separate code chunk for each step):

1. Calculate the mean of the outcome variable (e.g., home ownership rates).
2. Use your mean as a prediction: Add a new variable to the dataframe that consists of the mean of the outcome.
3. Calculate a summary measure of the errors for each observation---the difference between your prediction and the outcome. 
4. Calculate the mean of the outcome at levels of a predictor variable. (Find the conditional mean homeownership rate over a second variable of your choosing from the dataset.) 
5. Use these conditional means as a prediction: for every county, use the conditional mean to provide a ''best guess'' as to that county's level of the outcome.  
6. Calculate a summary measure of the error in your predictions.
7. Was your conditional mean prediction an improved estimate? How do you know?

Refer to the week 2 async .Rmd file for code suggestions.

Submit your assignment as `assignment2_<yourlastname>.Rmd`, where `<yourlastname>` is your last name (you do not need to include the < > around your last name.) Remeber to also include a knitted file.

I expect that the `.Rmd` file you submit will run cleanly, and that there shouldn't be any errors. Use LOTS of comments to tell me what you are doing.
