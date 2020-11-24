# automated-eda
Data explorartion process is a lengthy process and takes a lot of time.Automating some of the things makes our work easier.What each part of the project does is explained below


1)This Plots a histogram for all the numerial columns in a data set(We used a specific data set.Any data set can be passed on to this function) and saves all the histogram images in the working directory.

2)Created a function called graphs which takes your data set - plots histogram and box plot for numerical variable and plots bar plot for your categorical variables.You have to pass your data frame as a parameter

3)This function takes an optional parameter where you need to give the column number for which you need the plots and the data frame. It will give corresponding plots

4)Here we have a function called GetPath that creates a folder for storing images and if the folder already exists it directly stores iages in the path(Histogram,Boxplot and bar plot)

5)Here we have designed a function that will do following things for us >>Give all the details about our data set >>replace the missing vale with mean >> Removing Duplicates and after this you will get a new data set without missing values and duplicates .
There are few more functions which you can apply to specific columns.You can pass the column numbers and the function wiill give you the IQR,Value count for categorical variable,coeficiant of variation and univariate relationship table(crosstab)


The CSV files we used are uploaded as 'Attrition.csv' and 'Bengaluru_House_Data.csv'

Data dictionary for Attrition.csv - https://github.com/chithu1992/automated-eda/blob/main/Attrition_Data_Dictonary.xlsx
