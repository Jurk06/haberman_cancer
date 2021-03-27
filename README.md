# haberman_cancer

There are 306 observations with 4 features in the data set.
It is an imbalanced dataset with-
           a. 225 patients belonging to status 1, those who survived for 5 years and longer and
           b. 81 patients belonging to status 2, those who survived for less than 5 years.
Using scatter plot(Bi-variate analysis) -
           a. Most of the people have zero positive_lymph_nodes.
           b. We cannot distinguish between the people who survived and who didn't survive.
Using Pair-plot concept(Bi-variate analysis)-
           a. positive_lymph_nodes VERSUS Age is the useful plot to atleast get the insight that most people who survived have 0 postive lymph nodes detected.
           b. Age and Operation_Year have overlapping curves which makes difficult for classifying the survival status.
           c. but we cannot distinguish the data easily with the help of these plots as most of them are overlapping.                          
Using PDFs(Uni-variate Analysis)-
           a.  both Age and Operation_Year are not good features for useful insights as the distibution is more similar for both people who survived and also dead.
           b. positive_lymph_nodes is the only feature that is useful to know about the survival status of patients as there is difference between the distributions for both classes(labels). From that distibution we can infer that most survival patients have fallen in to zero positive_lymph_nodes.
           c. More number of people are not survived in year of operation of 1965.
Using CDFs(Uni-variate analysis)-
           a. We can observe that almost for all the features the statistics are similar except for positive_lymph_nodes.
           b. We can infer that patients above 46 axillary nodes detected can be considered as dead within 5 years. So,People having less number of positive_lymph_node have survived over 5 years.
The mean(average) of positive_lymph_nodes is more for people who died within 5 years than people who have survived for more than 5 years.
Mean age of patients who survived is 52 years and who didn't survive is 54 years.
Using Box plot and Violin plots-
           a. The number of positive lymph nodes of the survivors is highly densed from 0 to 5.
           b. Almost 80% of the patients have less than or equal to 5 positive lymph survived more than 5 years.
           c. From box plots and violin plots, we can say that more no of patients who are dead have age between 46-62,year between 59-65 and the patients who survived have age between 42-60, year between 60-66. 
Using Contour plot-
           a. There are more number of people who have undergone operation during the year 1959 - 1964 period and between the ages 42 - 60.
