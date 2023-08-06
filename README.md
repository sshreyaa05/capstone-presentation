# capstone-presentation
This project helps us to predict diabetes leveraging different machine learning algorithms that can predict whether an individual is likely to have diabetes or not 
based on their lifestyle related attributes and historical data.
## 1. Total count and their percentages of diabetic and non-diabetic cases.
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/02547f02-fc59-4947-a063-cf8dacd9bc68)
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/b44fe3e2-2291-48cc-b9f9-ef001fe18d29)
## =>> OVERVIEW :
## Here, getting the total count and percentages of who had diabetes and who did not have diabetes............so, as we can see
## that, count of non-diabetic women is the highest.
## 2. distribution of blood pressure by outcome.
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/3f25e796-ded5-441e-b238-aa0ec5579744)
## =>> OVERVIEW :
## From the above visualisation I can say, that the distribution of Blood Pressure of a person both with diabetes
## is slightly left skewed and whereas, without diabetes is almost normally distributed.
## 3. distribution of pregnancies by outcome.
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/89ee253b-788c-4568-9920-ab4141d69a5d)
## =>> OVERVIEW :
## From the above plot , I can easily interpret that the distribution of Pregnancies in female is right
## skewed , both with the diabetic and non-diabetic conditions, that says that , the mean is greater
## than the median.
## 4. frequency distribution of each features
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/9fcd8da5-32a4-46e9-8730-cefda1711720)
## =>> OVERVIEW :
## From the above plots I came to know regarding the distribution of various features in the data, that is, the
## distribution of some of the features are right skewed, which tells us that the mean is greater than the
## median,such as ,'Pregnancies','Skin Thickness','Insulin','Diabetes Pedigree Function' ,'BMI' and 'Age',these
## features are right skewed. On the otherhand, the feature, 'Blood Pressure' is slightly left skewed,
## that is, median is greater than mean.
## 5. correlation plot
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/1ee987f5-84cb-42f7-979b-c4ce0d351f34)
## =>> OVERVIEW :
## From this viasualisation, we can see that :
## ** If it is nearer to 1, then it says that the two variables are perfectly correlated to each other.
## ** If, it is nearer to -1, then it means the two variables are poorly correlated to eachother.
## As, we can see from the table and heatmap, the pairs which are correlated are:
## ** Age and Pregnancies
## ** Skinthickness and BMI
## ** Glucose and Insulin
## 6. plot of insulin vs outcome
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/67e109b6-2ad5-4c5d-a11e-4dc84abc8501)
## =>> OVERVIEW :
## Hereby, it is pretty understandable that the maximum people with non-diabetic condition is having a Insulin
## level in the range of (0-200)mL, as its showing that its wider as compared to that of those who are diabetic
## (less people). However, we can also see that the median value of Insulin level is more in diabetic females as
## compared to that in non-diabetic females, also along with the maximum number of outliers in this category.
## 7. boxplot of the dataset drawing various statistical inferences.
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/2d4c6275-2526-48b3-a12e-fd92f9ea67c7)
## =>> OVERVIEW :
## From the above visualization, I would interpret that all the features(independent variables) are containing
## outliers , we need to remove it in order to get a good outcome from this dataset.
## lastly, we can conclude that, after training the models and evaluating their performances we come with the conclusion that the random forest is the best performing model 
## inorder to solve the diabetes prediction with the highest recall value 0.60 among all the four models employed by us, thereby fetching its confusion matrix.
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/30074dfa-c79e-40c0-8cf4-5de96249f4d5)
## Hence, displaying the feature importances plot
![image](https://github.com/sshreyaa05/capstone-presentation/assets/132264752/c995476f-613c-4163-aee2-8370b824a7a3)
## Top 5 features, playing the most significant role in influencing the diabetes prediction
## . Glucose
## . Body mass index
## . Age
## . Diabetes pedigree function
## . Pregnancies




