# Intro-to-Analytics
 The project includes the following three main tasks:

(1) Data pre-processing (dealing with missing values, dropping ID-like columns, data aggregation, etc.) as appropriate.

(2) Descriptive statistical analysis of the data (charts, graphs, interactions, etc) as appropriate.

(3) Statistical modelling. 

 

Important notes about the project:
* The project needs to be on multiple linear regression (where the response variable is numerical).
* CLARIFICATION: A variable that is either 0 or 1 is called "binary" categorical (even though you might think it's numerical). In particular, any variable that has only two possible values would be binary categorical in general. Also, suppose each state of Australia is encoded as an integer between 1 and 8. This would still be a categorical variable! For categorical response variables, we use logistic regression, not linear regression. Logistic regression is discussed in Section 9.5 in our textbook, but it's beyond our scope. For this reason, you must stay away from using a categorical variable as your response variable and use a proper numerical variable as your response variable in your project. On the other hand, you can still have as many categorical independent variables as you like, there is nothing wrong with that.
* Incidentally, multiple linear regression is one of the workhorse methods of supervised machine learning when the response variable is numeric, so you can practically consider your project to be a "machine learning" project if you will.
* This is a loosely defined project to give you the maximum level of flexibility. In particular, you will need to choose a project topic yourself.
* Even though there are no hard restrictions on the project topic, the topic you choose must apparently be appropriate for a major course project. For instance, you may not use the same dataset in the sample project.
* As a guideline, your dataset needs to have at least 5 features (other than your response variable) and at least 200 rows. There is no upper limit on the number of rows, but if your dataset has more than, say 10,000 rows, you might want to select a random subset with at most 10,000 rows for ease of computation. That is, you will not lose any points for selecting only a relatively small subset of rows in case your dataset has too many rows.
* In general, time series data will not be appropriate for your course project. That is, if your data has a strong time dimension that you cannot ignore, you must find another topic.
* Your report's data exploration section needs to contain at least 2 (meaningful!) plots of each one of the following: one-variable plots, two-variable plots, and three-variable plots. That is, you need to have at least 6 plots all together. Your report also needs to contain some sort of variable section. You can see an example of this in the sample project report together with all the Python code to achieve this. 
* Sum of the text portions of your reports (that is, materials other than your computer code and their outputs such as tables, graphs, etc.), should be between 3 to 10 pages (if it were to be converted to a PDF file, but of course, you will submit HTML files, so this is just for a guideline). Together with your computer code and their outputs (tables, graphs, etc.), your reports should be between 10 to 40 pages.
