1. Firstly I imported all the necessary libraries and dataframe
2. Then, all the NA cells of each numeric column is filled with the median of the respective columns
3. Also, all the categoricsla columns such as 'census_msa', 'age_group', 'education', 'race' etc are dropped
4. These I have done for both test dataframe as well as training dataframe
5. For the training model I have used the Gaussian Naive Bias model and got the probability prediction for each of h1n1_vaccine and seasonal_vaccine
6. I have created a new csv file and put the contents there, some of the syntax for this part was not known so I took help from the internet
