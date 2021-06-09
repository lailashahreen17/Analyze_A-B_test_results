# Analyze_A-B_test_results
This projects introduces a very well known process of testing hypothesis test i.e  A/B test. For this project, I worked to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. My goal was to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

# Software used
* Pandas
* Numpy
* Stasmodel
* Seaborn
* Norm
* Matplotlib

# Dataset Used
* ab_data.csv:This dataset contains the info about users and thier engagement type with the webpage and whether they were in a control group or in an experiment group.
* countries.csv:This dataset contains the user id and their countries.

# Summary of Results
* From above data analysis for all three parts and results(Probablity,A/B testing,Regression Approach) we can advise the company in general that there is not really strong evidence or reason for leaning toward new page implementation.

* In reality, we are lacking many other information about new page quality (i.e. any attractive feature added or not could be an option to see the effect) which really benefits the end users to go for it. Also adding other variables such as data about users themselves or duration of their visit could bring insights on conversion rate from old page to new one.

* We also do not have any revenue data(expense on implementing new page vs. revenue on increasing traffic) which could be ultimate importatnt factor behind the changes. So at this point, we have to maintain old page based on current data analysis.

* The sample size is large enough for both the pages, so we are good on that part. For future analysis, we should go for individual statistics to attain better accuracy of our findings( may be applying the machine learning techniques can assist).**


# Acknowledgements
I find a great opprtunity through DAND program of Udacity. I could utilized my data analysis and hypothesis test skills learned from classroom lessons and also apply in this particular project. Other references are mentioned in the notebook itself.Last but not the least, I am thankful to the mentors as well for occassional support of my queries in regard to this project.





