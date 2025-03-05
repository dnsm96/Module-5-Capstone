# Capstone Module 5

### **1. What is a vector in mathematics?**

A vector is an 1D array, which has both magnitude and direction.

for example: a car moving towards North at 75km/h can be shown as a vector by (0,75)

### **2. How is a vector different from a scalar?**

A scalar only has magnitude, while a vector has both magnitude and directions

example:

speed: shows how fast an object is moving - Scalar

Velocity : shows how fast an object is moving and in what direction - Vector

### **3. What are the different operations that can be performed on vectors?**

Addition (Vector + Vector)

Subtraction (Vector - Vector)

Dot product (Vector * Vector)

Cross product (3D Vectors)

Scalar multiplication (Vector * scalar)

### **4. How can vectors be multiplied by a scalar?**

A vector scalar multiplication is done by simply multiplying all the vector values by the scalar value

for example, we have a 2d vector (2,4) and a scalar values 5

the multiplication would be (2*5, 4*5) resulting in (10,20)

### **5. What is the magnitude of a vector?**

A magnitude is the length of a vector from the starting to the end point.

for a 2d vector(v) of (3,4), the magnitude(|v|) can be calculated as below

|v| = sqrt(3^2 + 4^2) ⇒ 25

A magnitude of a vector is always a positive values

### **6. What is the difference between a square matrix and a rectangular matrix?**

A square matrix has equal number of rows and columns, where as a rectangular matrix has different number of rows and columns

### **7. What is a linear transformation in linear algebra?**

Linear transformation is changing the vector while preserving the magnitude and direction 

Example: Rotating a vector without changing its length

### **8. What is an eigenvector in linear algebra?**

An eigenvector is a special kind of vector that does not change direction when a linear transformation (matrix multiplication) is applied. Instead, it is stretched or shrunk by a scalar factor called an eigenvalue.

### **9. What is the gradient in machine learning?**

Gradient is like a slope that tells us how to change models parameters (weights) to reduce errors in prediction. Gradient is mainly used in Gradient descent, which is used to minimize the loss function while training a machine learning model.

### **10. What is backpropagation in machine learning?**

The process of readjusting the mode parameters based on the errors made by propagating the error backwards is called backpropagation 

### **11. What is the concept of a derivative in calculus?**

It is the rate of change of a function with respect to a variable. It tells us how the functions output changes when we make a small change in the input

### **12. How are partial derivatives used in machine learning?**

Partial derivatives are used in machine learning to optimize the model parameters by computing the rate of change of a function with respect to one variable while keeping others variables constant.

### 13. **What is probability theory?**

It is a part of mathematics that deals with uncertainty. It helps us understand the probability of an event happening, which in turn helps make predictions.

### 14. **What is conditional probability, and how is it calculated?**

A conditional probability is the probability of an even happening, given that an event has already happened. 

Mathematically it is calculated by:

p(A n B) / p(B)

where p(A n B) is the joint probability of both events A and B occurring together

p(B) is the probability of even B

### **15. What is Bayes theorem, and how is it used?**

Bayes theorem, Is a fundamental concept in probability, which helps update the probabilities based on a new evidence.

It can be used in spam filtering by updating the probability of an email being a spam given it has some key words, like lottery or free money

### 16. **What is a random variable, and how is it different from a regular variable?**

A random variable is depended on an outcome of an random event. It does not have a fixed outcome like regular variables. 

for example: 

The probability of getting heads by flipping a coin 

There are two main types of random variables:

1. Discrete Random Variable : Takes countable values
2. Continuous Random Variable : Take uncountable Values

### 17. **What is the law of large numbers, and how does it relate to probability theory?**

The law of large numbers states that, the sum of mean values of samples will be very close to the expected value of the population. As the number so samples increase the value gets closer and closer to the expected value

The law of large number states that the more we repeat a random experiment, the more accurate our probability estimates will be

### 18. **What is the central limit theorem, and how is it used ?**

It states that, if given sufficiently large sample size the distribution of sample mean will be approximately normally distributed regardless of the original distribution 

This can be used in for following purposes:

**Confidence intervals** : Since the sample mean in approximately normally distributed, we can use the properties of normal distribution to estimate intervals

**Hypothesis Testing :** By assuming sample mean follows normal distribution we can calculate test statistic and p-value

### 19. **What is the difference between discrete and continuous probability distributions?**

The discrete probability distribution takes finite number of values and uses probability mass function 

The continuous probability distribution take infinite values and use probability density function 

### **20. What are some common measures of central tendency, and how are they calculated?**

The most common measures of central tendency are Mean, Median and Mode

Mean : It is the average of the data

Median : It is the centermost value

Mode: It is the most repeated value

### 21. **What is the purpose of using percentiles and quartiles in data summarization?**

Percentile and Quantile helps summarization by providing useful insights about the spread and distribution of the data

While percentile divides the data into 100 equal parts, where nth percentile represents n% of data lies below the nth point

Quantile on the other hand divides the data into 4 equal parts

1st quantile Q1 represents the 25% of the data falls below that point 

2nd quantile Q2 represents the 50% of the data falls below that point 

3rd quantile Q3 represents the 75% of the data falls below that point 

### **22. How do you detect and treat outliers in a dataset?**

There are different methods of detecting outliers. Mainly divided into statistical and visualization 

Visualization methods  include Scatterplot, box plots, and histograms to identify outliers.

Statistical methods include: 

1. Z-Score: calculating score for each data point and typically score above 3 and below -3 are considered outliers 
2. IQR (Interquartile Range): Calculate IQR which is the range between Q3 and Q1 and data points below Q1−1.5×IQR and data points above  Q3+1.5×IQR are considered outliers

### 23. **What is a joint probability distribution?**

A joint probability distribution shows the likelihood of two or more random variables occurring simultaneously. It shows how multiple variables are related to each other.

**Types of Joint probability distribution :** 

1. **Discrete Joint Probability Distribution**
    
        For Discrete random variables 
    
2. **Continuous Joint Probability distribution**
    
        For Continuous random variables 
    
3. **Marginal distribution**
    
       It is obtained by summing or integrating other random variables 
    
4. **Conditional distribution**
    
      It shows the probability of one random variable give the value of another
    

### **24. What is the difference between a joint probability distribution and a marginal probability distribution?**

Joint Probability Distribution is the probability of two or more events happening simultaneously while Marginal Probability distribution is the probability of an even happening regardless of other events

**example for Joint Probability distribution :** The probability of getting a 4 in one die and 2 in another die while rolling them simultaneously 

**example for Marginal Probability distribution :** The Probability of rolling 3 on one die regardless of the other die

### 25. **What is the covariance of a joint probability distribution?**

The covariance is the extent to which two random variables change together. The covariance of the joint probability distribution quantifies the linear relationship between two variables.

Mathematically the covariance for two variables X, Y can be denoted as 

cov(X, Y) = E[(X - 𝜇x)(Y - 𝜇y)]

where E represents the mean

where 𝜇x is the mean of X

where 𝜇y is the mean of Y

### 26. **How do you determine if two random variables are independent based on their joint probability distribution?**

To check if the random variables are independent we can check if knowing the value of one variable gives information about the other variable. If it doesn’t they are independent

Here’s how we can check:

step 1: Find the joint probability of two variables happening together 

Step 2: Find the marginal probability of each variable happening on its own

step 3: Multiply the marginal probability of individual variables, if the resultant value matches the join probability then the variables are independent 

### 27. **What is the relationship between the correlation coefficient and the covariance of a joint probability distribution?**

Both correlation and covariance measure the relationship of the random variables, however there is a slight difference between them

Covariance measure the degree to which variables change together, it can take any value between negative infinity to positive infinity 

Correlation is more standardized version of covariance, it ranges between -1 and +1. It measures the strength and direction of the linear relationship between the variables 

### 28. **What is sampling in statistics, and why is it important?**

Sampling is taking part of the population in assumption that it represents the entire population.

There are multiple methods of sampling like Random sampling, convenience sampling etc.,

Sampling is important in statistics because, most of the times in real world scenarios its impossible to get all the population data. Hence sampling helps in gaining insights from the data by reducing cost and effort 

### 29. **What are the different sampling methods commonly used in statistical inference?**

**Simple Random Sampling:** Selecting from the population randomly without any bias

**Systematic Sampling:** Selecting every Kth value from the population starting with a random starting point

**Stratified Sampling:** Diving the population into homogenous groups and selecting at random from those groups

**Cluster Sampling:** Diving the population into clusters and selecting randomly from the clusters

**Convenience Sampling**: Selecting based on ease of access

**Snowball Sampling:** Selecting based on references

**Quota Sampling:** The sample is chosen to reflect certain characteristics of the population. The selection within each quota is non-random

### 30. **What is the central limit theorem, and why is it important in statistical inference?**

The central Limit Theorem states that given sufficient number of samples, the distribution of sample mean will be normally distributed regardless of the distribution of the population. As the number of samples increase the data will be more and more normally distributed

**Importance of CLT:**

 1 . Simplifies the analysis as it allows the use of normal distribution approximation for hypothesis testing and confidence intervals

1. Acts as a foundation of inferential statistics as many statistical models assumes a normally distributed data
2. In real world scenarios its often not possible to get the distribution of the population data

### **31. What is the difference between parameter estimation and hypothesis testing?**

 **Parameters estimation** is estimating the population parameters like mean, median from the sample data 

Types: 

1. Point Estimation : Provides a single value of estimate of the parameter 
2. Interval Estimation : Provides a range within with the population parameters would lie

 **Hypothesis Testing** is making decision about the population parameter by testing a specific       hypothesis. It assesses whether the evidence from the sample data either supports or contradicts the hypothesis

### 32. **What is the p-value in hypothesis testing?**

P-Value(probability value) is the probability of obtaining a value at least as extreme as the observed value assuming null hypothesis is true. It quantifies how likely your sample data would be if the null hypothesis is true

### 33. **What is confidence interval estimation?**

It is a statistical method used to estimate range of values within which a population parameter(like mean) is likely to fall with a certain level of confidence. Instead of providing a single estimate confidence interval provides a range of values, reflecting the uncertainty

### 34. **What are Type I and Type II errors in hypothesis testing?**

Type I error is rejecting the null hypothesis when its True.

Ex: Medical test incorrectly detects a disease in a healthy person

Type II error is failing to reject the null hypothesis when its False

Ex: Medical test fails to detect a disease in a sick person

### 35. **What is the difference between correlation and causation**

Correlation measure the strength and direction of linear relationship of the variables

Causation implies that one variable directly affect the change in another variable

### 36. **What does the confidence level represent in a confidence interval?**

The confidence level in the confidence interval denoted the level of confidence that a population parameter lies within the confidence interval

**Interpretation :** A 95% confidence level means that if we were to take many random samples from the population and construct confidence intervals for each sample, approximately 95% of those intervals would contain the true population parameter.

### 37. **What is hypothesis testing in statistics?**

Hypothesis testing is used to make decisions or draw conclusions about a population parameter based on a sample data. It involves formulating a hypothesis, collecting data and using statistical tests to determine whether there is enough evidence to support or reject the hypothesis

### 38. **What is the purpose of a null hypothesis in hypothesis testing?**

Null hypothesis is a default assumption in hypothesis testing, it assumes there no effect, no difference, no relationship in the population 

Example : 

Hypothesis  - A new drug improves recovery time

Null Hypothesis  - There is not improvement in recovery time

Alternative Hypothesis - There is improvement in recovery time

### 39.**What is the difference between a one-tailed and a two-tailed test?**

One-Tailed test : 

It assesses whether a parameter is greater than or less than a certain value. It tests for deviation in one direction

Two-Tailed test: 

It tests where the parameter is significantly greater that the given value, regardless of the direction. It tests for deviation in both sides

### **40. What is experiment design, and why is it important?**

It is the process of planning and structuring the experiment to ensure it answers the research question or effectively tests a hypothesis 

A well designed experiment design ensures that the results are valid and accurately reflect the relationship between the variables 

### **41. What are the key elements to consider when designing an experiment?**

1. Hypothesis : A clear statement about the expected relationship between the variables
2. Variables:
    1. Independent Variable : The variable that is manipulated by researcher
    2. Dependent Variable : The variable that is observed 
    3. Control Variable: The variables that are kept constant
3. Groups:
    1. Experiment Group: The group that is experimented upon
    2. Control Group: The group that serves as  a baseline
4. Randomization : Selecting the samples random manner
5. Replication: Repeating the experiment to check if the results are consistent
6. Data collecting: Deciding how the data will be collected 
7. Analysis: Determining the statistical method to analyze the data and draw conclusions 

### **42. What is the left-skewed distribution and the right-skewed distribution?**

Left-Skewed distribution: Also know as negatively skewed, it means most of the data are concentrated on the right side of the distribution while few outliers lie on the left side. Mean is usually lower than median 

Right-Skewed distribution: Also know as positively skewed, it means most of the data are concentrated on the left side of the distribution while few outliers lie on the right side. Mean is usually higher than median 

### **43. What is Bessel’s correction?**

It is a technique used to adjust the calculation of the sample variance and standard deviation in order to make them unbiased estimators of the population variance and standard deviation

### **44. What is kurtosis?**

It is a statistical measure that describes the shape of the distributions tail with respect to its overall shape.

Types of Kurtosis:

1. Mesokurtic: Distributions with kurtosis similar to a normal distribution
2. Leptokurtic: Distributions with heavier tails and a sharper peak compared to a normal distribution
3. Platykurtic: Distributions with lighter tails and a flatter peak compared to a normal distribution.

### 45. **What is the difference between Descriptive and Inferential Statistics?**

Descriptive statistics summarize and describes the main features of the data. It provides a snapshot of the data’s characteristics without making predictions or generalizations beyond the sample itself.

Examples: Measures of central tendency, Data visualization 

Inferential statistics go beyond the data at hand to make predictions, generalizations, or conclusions about a larger population based on a sample.

Example : Hypothesis Testing, probability distribution

### 46. **In an observation, there is a high correlation between the time a person sleeps and the amount of productive work he does. What can be inferred from this?**

Based on the observation we can infer that the amount of time a person sleeps directly relates to the output a person produces from work. Lesser the sleeps a person gets lesser the productivity of the work is and If the person is well slept he can be a lot more productive in his work.

### 47. **If there is a 30 percent probability that you will see a supercar in any 20-minute time interval, what is the proba­bility that you see at least one supercar in the period of an hour (60 minutes)?**

If the probability of seeing a supercar in a 20-minute interval is 30% (or 0.30), then the probability of not seeing a supercar is 1−0.30 =  0.70

There are three 20 minutes in 60 minutes, then the probability of not seeing a supercar in 60 minutes is 0.7 * 0.7*0.7 = 0.343

Then the probability of seeing a super car in 60 minutes is 1 - 0.343 = 0.657

We have a probability of **65.7%** of seeing a supercar in 60 minutes.

### 48. **What factors affect the width of a confidence interval?**

The confidence interval are affected by following factors:

1. Sample size : Larger sample sizes generally lead to narrower confidence intervals because they provide more information about the population.
2. Confidence Level : Higher confidence levels result in wider confidence intervals.
3. Variability in the Data: Greater variability or standard deviation in the data leads to wider confidence intervals.
4. Standard Error : The standard error is directly related to the width of the confidence interval.
5. Population Variance or Standard Deviation: Higher population variance or standard deviation leads to wider confidence intervals.

### 49. **How does sample size influence the width of a confidence interval?**

**Effect of Sample Size:**

1. **Larger Sample Size → Narrower Confidence Interval**
2. **Smaller Sample Size → Wider Confidence Interval**

Why :

1. **More Data = More Accuracy**
    - A larger sample gives a better estimate of the population, reducing uncertainty.
2. **Standard Error Decreases**
    - As sample size increases standard error decreases making the confidence interval narrower
3.  **Higher Precision**
    - A smaller confidence interval means we are more **certain** about our estimate.

### 50. **What is a t-test?**

A t-test is a statistical test used to compare the means of two groups and determine if the difference is significant. It is useful when the sample size is small and the population standard deviation is unknown

A t-test helps determine if two means are significantly different or just due to chance.

Types of t-test: 

1. **One-Sample t-test** : Compares a sample mean to a known population mean
2. **Two-Sample t-test :** Compares the means of two independent groups
3. **Paired t-test :** Compares before and after measurements within the same group
